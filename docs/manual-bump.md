
## Manual Version Bump Process
Sometimes the version of the edgex-global-pipelines needs to be changed between `stable` and `experimental` tags in order to enhance and validate that the changes work as expected.

The process documented here outlines the manual process for bumping the version and tag on the global libraries.

### Committer Access Required 
You must have write access to the repo to perform this manual version bump process.
 - Developer must be a member of the devops-core-team as per TSC approval
 - Version info can be obtained through view of the Jenkins Pipeline log for last successful build

```
$ git clone git@github.com:edgexfoundry/edgex-global-pipelines.git
$ cd edgex-global-pipelines
$ ./scripts/update-named-tag.sh <version> <stable / experimental>
```



### Click on image below to view ASCII recording of the manual version bump process
[![Manual Bump Process](/docs/images/manual-bump-asciicinema.png)](https://asciinema.org/a/gxtkk9fY04xZMvqreH298b1NP "ASCII Recording of Manual Version Bump Process")