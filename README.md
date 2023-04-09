# How to contribute with us?

If you want to do a contribution in one of our repositories, first, thanks a lot 😊 And second, please follow the next steps.

## 1. Fork

Go to the repository where you want to contribute, then
in the right side you will see a botton called **Fork**,
do click and then click in **Create new fork**

![images](/.images/fork.png)

This will create a copy of the repository in your Github profile.

## 2. Clone

Go to your Github profile and check the copy of the repository, go there, it should have a message saying the repository is forked.

Example:

![images](/.images/clone1.png)

Copy the url of the repository and clone it in your personal computer

![images](/.images/clone2.png)

```
git clone <insert url>
```

## 3. Create your branch

```
git checkout -b <insert name of the branch>
```

## 4. Do your contribution

Do your modifications and then:

```
git add <insert the file you modified>
```

```
git commit -m "<insert message>"
```

The message should follow the
[convention](https://www.conventionalcommits.org/en/v1.0.0/)

## 5. Rebase

Add the repository source as remote
(in this case, it is the repository
located in geocodev).

```
git remote add upstream <insert the url of the repository source>
```

Verify if the repository source is added in the list of remotes.

```
git remote -v
```

```
git pull --rebase upstream main
```

## 6. Push

```
git push origin <insert name of the branch>
```

## 7. Open pull request

![images](/.images/pull_request.png)

Go to the repository source, you will see the
pull request opened:

![images](/.images/pull_request2.png)