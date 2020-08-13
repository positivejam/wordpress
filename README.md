# About this fork

The purpose of this fork is to allow building the Wordpress Docker image, with modifications to include XDebug.

## Keeping this fork in sync with upstream
This is for my own reference, to do each time upstream gets ahead of mine; from this article: [https://help.github.com/articles/syncing-a-fork/]()

1. Fetch the branches and their respective commits from the upstream repository. Commits to `master` will be stored in a local branch, `upstream/master`.

    ```bash
    $ git fetch upstream
    ```
2. Check out your fork's local `master` branch.

    ```bash
    $ git checkout master
    ```
3. Merge the changes from `upstream/master` into your local `master` branch. This brings your fork's `master` branch into sync with the upstream repository, without losing your local changes.

    ```bash
    $ git merge upstream/master
    ```
4. Push the changes to remote.

    ```bash
    $ git push
    ```

# About this Repo

https://github.com/docker-library/wordpress

## Maintained by: [the Docker Community](https://github.com/docker-library/wordpress)

This is the Git repo of the [Docker "Official Image"](https://github.com/docker-library/official-images#what-are-official-images) for [`wordpress`](https://hub.docker.com/_/wordpress/) (not to be confused with any official `wordpress` image provided by `wordpress` upstream). See [the Docker Hub page](https://hub.docker.com/_/wordpress/) for the full readme on how to use this Docker image and for information regarding contributing and issues.

The [full image description on Docker Hub](https://hub.docker.com/_/wordpress/) is generated/maintained over in [the docker-library/docs repository](https://github.com/docker-library/docs), specifically in [the `wordpress` directory](https://github.com/docker-library/docs/tree/master/wordpress).

## See a change merged here that doesn't show up on Docker Hub yet?

For more information about the full official images change lifecycle, see [the "An image's source changed in Git, now what?" FAQ entry](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

For outstanding `wordpress` image PRs, check [PRs with the "library/wordpress" label on the official-images repository](https://github.com/docker-library/official-images/labels/library%2Fwordpress). For the current "source of truth" for [`wordpress`](https://hub.docker.com/_/wordpress/), see [the `library/wordpress` file in the official-images repository](https://github.com/docker-library/official-images/blob/master/library/wordpress).

---

-	[![build status badge](https://img.shields.io/github/workflow/status/docker-library/wordpress/GitHub%20CI/master?label=GitHub%20CI)](https://github.com/docker-library/wordpress/actions?query=workflow%3A%22GitHub+CI%22+branch%3Amaster)
-	[![build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/update.sh/job/wordpress.svg?label=Automated%20update.sh)](https://doi-janky.infosiftr.net/job/update.sh/job/wordpress/)

| Build | Status | Badges | (per-arch) |
|:-:|:-:|:-:|:-:|
| [![amd64 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/amd64/job/wordpress.svg?label=amd64)](https://doi-janky.infosiftr.net/job/multiarch/job/amd64/job/wordpress/) | [![arm32v5 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm32v5/job/wordpress.svg?label=arm32v5)](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v5/job/wordpress/) | [![arm32v6 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm32v6/job/wordpress.svg?label=arm32v6)](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v6/job/wordpress/) | [![arm32v7 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm32v7/job/wordpress.svg?label=arm32v7)](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v7/job/wordpress/) |
| [![arm64v8 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/wordpress.svg?label=arm64v8)](https://doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/wordpress/) | [![i386 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/i386/job/wordpress.svg?label=i386)](https://doi-janky.infosiftr.net/job/multiarch/job/i386/job/wordpress/) | [![mips64le build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/mips64le/job/wordpress.svg?label=mips64le)](https://doi-janky.infosiftr.net/job/multiarch/job/mips64le/job/wordpress/) | [![ppc64le build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/wordpress.svg?label=ppc64le)](https://doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/wordpress/) |
| [![s390x build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/s390x/job/wordpress.svg?label=s390x)](https://doi-janky.infosiftr.net/job/multiarch/job/s390x/job/wordpress/) | [![put-shared build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/put-shared/job/light/job/wordpress.svg?label=put-shared)](https://doi-janky.infosiftr.net/job/put-shared/job/light/job/wordpress/) |

<!-- THIS FILE IS GENERATED BY https://github.com/docker-library/docs/blob/master/generate-repo-stub-readme.sh -->
