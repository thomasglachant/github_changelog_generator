# Docker GitHub Changelog Generator image
This container generates your GitHub CHANGELOG.md by using [GitHub Changelog Generator](https://github.com/skywinder/github-changelog-generator).

Based on [prooph work](https://github.com/prooph/docker-files/blob/master/github-changelog-generator/master/Dockerfile)

## Generate the Changelog
Run the following command with your arguments.

```bash
$ docker run -it --rm -v $(pwd):/app thomasglachant/github-changelog-generator
```
