## GitHub Workflow

We're following basic GitHub Flow. If you have no idea what we're talking 
about, check out [GitHub's official guide](https://guides.github.com/introduction/flow/). 
Note that merge is only performed by the repository maintainer.

Guide for performing commits:

* Isolate each commit to one component/bugfix/issue/feature
* Use a standard commit message format:

>     [component/folder touched]: Description intent of your changes
>
>     [List of changes]
>
> 	  Signed-off-by: Your Name your@email.com

For example:

>     swss-common: Stabilize the ConsumerTable
>
>     * Fixing autoreconf
>     * Fixing unit-tests by adding checkers and initialize the DB before start
>     * Adding the ability to select from multiple channels
>     * Health-Monitor - The idea of the patch is that if something went wrong with the notification channel,
>       we will have the option to know about it (Query the LLEN table length).
>
>       Signed-off-by: user@dev.null


* Each developer should fork this repository and [add the team as a Contributor](https://help.github.com/articles/adding-collaborators-to-a-personal-repository)
* Push your changes to your private fork and do "pull-request" to this repository
* Use a pull request to do code review
* Use issues to keep track of what is going on

##Responding to pull requests
Responsible individual: A contribution needs to be looked at by its 
maintainers. In the absence of the maintainer, the project leader can respond.
A pull request should be responded to in approximately 48 hours. This does 
not mean the contribution will be resolved in 48 hours.  It could even mean 
an email that states: “busy now, will get to it soon.” 

##Contributors License Agreement
All contributors must sign a contribution license agreement before 
contributions can be accepted.  In the near future, this process will
automatically trigger when submitting a pull request. Until then, we will 
send contributors a license agreement to be signed.
