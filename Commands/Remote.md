# git remote
>When working with git, a **remote** is any git repository tht is not the maching you're working on. The counterpart to this is **local**, or the machine that is being developed on.
>
>Take GitHub for example. While git the the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others.
>
>**Note**: While the repositories (local and remore) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote
>
>A remote can be added with the `git remote add` command, followed by the names and locattion of the remote.
>
>The name is a local name, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote add orgin https://github.com/ElevenFiftyAcademy/GitFundamentals.git
```

### Removing a remote 
>
>A remote can be removed with the `git remote remove` command. followed by the name of the remote.

```
git remote remove orgin
```

## Resources
- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to Home](../README.md)
