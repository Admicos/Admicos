| My Repos 404ing?
|-|
| Check https://git.ebc.li/archive |

---

I am no longer using GitHub to host anything other than forks for sending
patches upstream.

My new repos are split between [sourcehut](https://sr.ht/~admicos) and
[my own server](https://git.ebc.li), where the more "important" ones
will probably end up in the former.

I also accept patches and bug reports for my existing GitHub repos via
email.  

Send 'em here: [`~admicos/projects@lists.sr.ht`] ([view archives])

[`~admicos/projects@lists.sr.ht`]: mailto:~admicos/projects@lists.sr.ht
[view archives]: https://lists.sr.ht/~admicos/projects

Please edit your mail subject to refer to the project in question.

If you're using git send-email to send patches, which you __should__, 
run this in my repos after you've cloned them:

```sh
git config format.subjectprefix "PATCH projectname"
```
