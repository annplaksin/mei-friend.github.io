---
title: Environments
description: The mei-friend development environments
permalink: /docs/advanced/env/
layout: page
---
# mei-friend Environments    

We maintain three public-facing instances of mei-friend: 

* A production instance, available from <https://mei-friend.mdw.ac.at> and serving the '[main](https://github.com/mei-friend/mei-friend/tree/main)' branch of our codebase. This instance always serves the latest 'release' version of mei-friend. This instance is intended for general use – please use it unless you have a specific reason not to!
* A staging instance, available from <https://staging.mei-friend.mdw.ac.at> and serving the '[staging](https://github.com/mei-friend/mei-friend/tree/staging)' branch of our codebase. This is a 'public beta-testing' instance that may serve a more recent, as-yet unreleased version of mei-friend. Use this instance if you would like to see new, cutting-edge features before they make it to production. We do not push new code onto this instance unless it meets a certain minimal expectation of stability; however, please use this instance with caution, as code running here may not yet have been tested sufficiently for a general release. 
* A testing instance, available from <https://testing.mei-friend.mdw.ac.at> and serving the '[testing](https://github.com/mei-friend/mei-friend/tree/testing)' branch of our codebase. This is a 'public alpha-testing' instance that may serve version of mei-friend with untested and completely new features. Use this instance if you would like to see new, cutting-edge and potentially untested features before they make it to the staging instance. We may push new code onto this instance without having tested it severly for stability; please use this instance with caution. 

<figure class="figure halfwidth">
    <div class="figure-title">Fig.&thinsp;1: The mei-friend logo in the staging environment.</div>
    <img class="figure-img" src="{{ site.baseurl }}/assets/img/env/staging-menu-logo.png" 
        alt="The mei-friend logo in the staging environment" width="350px">
    <figcaption class="figure-caption">
        When you see this logo, you are using our staging ('public beta-testing') version of mei-friend. 
        Click on the logo in the interface to return to the production (stable release) version.
    </figcaption>
</figure>

Additionally, we maintain a '[develop](https://github.com/mei-friend/mei-friend/tree/develop)' branch of our codebase, used to run tests and integrate different streams of development until they are sufficiently mature for release to staging; and, a number of 'develop-*feature*' branches, used for independent development of specific features, which are merged into 'develop' once implemented. 

## Which environment am I using?
The current environment is reflected:
1. In the URL that mei-friend is being served from (see above);
2. In the mei-friend logo: when working from 'staging', this will feature a disclaimer (Figure&thinsp;1).
3. In the mei-friend version string at the bottom right of the interface; this will be prefixed by 'staging-', 'develop-', or 'testing-' (for those respective environments, see Figure&thinsp;2), or will simply feature a version number (when in the 'production' environment).


<figure class="figure twothirdswidth">
    <div class="figure-title">Fig.&thinsp;2: Screen shot of the mei-friend testing environment.</div>
    <img class="figure-img" src="{{ site.baseurl }}/assets/img/env/testing-screen-shot.png" 
        alt="The mei-friend logo in the staging environment">
    <figcaption class="figure-caption">
        A screen shot of our testing version ('public alpha-testing') of mei-friend showing the testing version of our owl mascot *Eulise*. 
        Click on the top-left logo in the user interface to return to the production (stable release) version. 
        The current mei-friend is automatically prefixed with 'testing-' in this environment.
    </figcaption>
</figure>

Please see the section on [developing mei-friend]({{ site.base_url }}/docs/advanced/dev) for further information on contributing to our codebase.

