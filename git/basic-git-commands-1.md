# Basic Git Commands

## git init

Initializes a local repository

```text
$ git init
```

## git add

Add a file to staging area

```text
$ git add <FILE_NAME>
```

{% hint style="info" %}
Staging area is just a list that contains the files that would be committed when a git commit is done

To add all files in the repository you can use the command below
{% endhint %}

```text
$ git add .
```

## git status

Check status of working tree

```text
$ git status
```

## git commit

Commit changes to local repository

```text
$ git commit -m '<COMMIT_MESSAGE>'
```

{% hint style="info" %}
&lt;COMMIT\_MESSAGE&gt; are descriptions added to commits to indicate changes that were made
{% endhint %}

## git push

Push local updates to remote repository

```text
$ git push
```

{% hint style="info" %}
For local repositories that are connected to multiple repositories, you can specify the repository to push to
{% endhint %}

```text
$ git push <REPO_NAME> <BRANCH>
```

{% hint style="info" %}
&lt;REPO\_NAME&gt; indicates the name of the remote repository being pushed to

&lt;BRANCH&gt; indicates the branch of the remote repository being pushed to

detailed description will be given in subsequent sections
{% endhint %}

## git pull

Pull latest updates from remote repositories

```text
$ git pull
```

{% hint style="info" %}
For remote repositories that are connected to multiple repositories, you can specify the branch to pull from
{% endhint %}

```text
$ git pull <REPO_NAME> <BRANCH>
```

{% hint style="info" %}
&lt;REPO\_NAME&gt; indicates the name of the remote repository being pulled from

&lt;BRANCH&gt; indicates the branch of the remote repository being pulled from

detailed description will be given in subsequent sections
{% endhint %}

