# icaps2026.github.io

Website for the ICAPS 2026 conference held in Dublin, Ireland - June 2026.

This site is published automatically via a GH Action workflow to the following default GH-pages:

<https://icaps2026.github.io/>

If you want information on how to setup and deploy a new web-page for future ICAPS, please refer to file [DEPLOYMENT.md](DEPLOYMENT.md) is useful for those setting up a new webpage for future ICAPS iterations.

## Instructions for proposing/submitting updates

Here are the instructions to submit updates to the website, for example, if you are the organizer of a workshop or tutorial and you want to update your own sub-page.

We follow the [standard workflow](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) for submitting/proposing updates to the upstream (original ICAPS26 website) using a Pull Request from a branch of a forked repo.

### 1. Fork the upstream ICAPS web repository

First you need your own forked copy of the original upstream website:

1. Sign up for Github
2. Go to <https://github.com/icaps2026/icaps2026.github.io> and click the '`Fork`' button in the upper right. This should create and bring you to your _own_ forked copy of the ICAPS website repository.

### 2. Clone your fork

Clone locally the just created fork. After successfully cloning the repository you should end up with a directory called `icaps2026.github.io`. This directory will be referred to as _website root_.

> [!NOTE]
> You may want to setup an upstream remote to track the original repo:
>
> ```shell
> git remote add upstream git@github.com:icaps2026/icaps2026.github.io.git
> git fetch upstream
> ```

You only need to do all this once.

### 3. Branch to make your edits

From your local repo of your fork, create a new branch for the pull request you plan to make:

```shell
git checkout -b my-feature-branch
```

### 4. Make Your Changes and Commit

Edit your files normally, commit, and push to your remote fork:

```shell
git add .
git commit -m "my updates"
git push -u origin my-feature-branch
```

> [!NOTE]
> The option `-u` set the upstream branch so that it is easier to push/pull later without specifying it explicitly every time.

### 5. Create a Pull Request (PR)

* Go to your fork on GitHub.
* Click “Compare & pull request”.
* Ensure the head repo is your fork repo, and the head branch is your feature branch.
* Ensure the base repo is the upstream repo, and the base branch is usually `main`.
* Add a clear title and description.
* Submit the PR to the upstream original ICAPS repo.

The website maintainers will be notified and (hopefully) approve the changes to the site (step 7) or request further changes (step 6).

### 6. Respond to Review

Upstream maintainers may request changes. Just push updates to the same branch in your fork and the Pull Request already created will include those new changes.

### 7. PRs is merged; sync your fork

It the upstream maintainers are happy with the PR updates, they will merge the PR into the upstream `main` branch, and changes submitted will go "live".

It is now good practice to sync your fork. You can do it from the GH interface or, since you have already setup an upstream remote:

```shell
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

Or use `rebase` (intead of `merge`) if preferred.

> [!NOTE]
> If you want you can just delete the branch in your fork. You will hopefully create a new branch for new updates anyways 😉

## Testing changes

The site is built with [HUGO](https://gohugo.io) framework for automated generation of static web content.

It is often convenient to develop and test locally your site _before_ pushing it to the remote repo (which kicks off the deployment workflow to re-build the site).

If you have [hugo installed](https://gohugo.io/getting-started/installing) on your system, you can test  your changes by running `hugo server` in the _website root_ folder. This will start a local webserver on <http://localhost:1313>:

```shell
$ hugo server
...
Built in 19 ms
Environment: "development"
Serving pages from disk
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```

The site can be accessed locally at http://localhost:1313/ and is locally produced in folder `public/` (not tracked by git).

### Creating your pull request

If you have future edits to make, you can restart the process at "[Branch to Make your Edits](https://github.com/icaps2026/icaps2026.github.io#branch-to-make-your-edits)"
