# EECS 201 HW 2
uniqname:  skunkel

## Question 1
``` 1
<html>
  <head>
    <title>Learn Git Version Control using Interactive Browser-Based Labs | Katacoda</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no,minimal-ui">
    <meta name="apple-mobile-web-app-capable" content="yes">
    
    <script type="text/javascript">window._trackJs = { token: '97f1dd886918463ebc84d187024d5aad', application: 'katacoda' };</script>
    <script type="text/javascript" src="https://cdn.trackjs.com/releases/current/tracker.js"></script>
    <script type="text/javascript" src="/js/vendor/webfont.js"></script>
    <script type="text/javascript">
      WebFont.load({
        google: {
          families: ['Open Sans', 'Source Code Pro']
        },
        custom: {
          families: ['franklingoturwtotbooregular']
        }
      });
    </script>
    <link type="text/css" rel="stylesheet" href="/css/materialize.min.css"  media="screen,projection"/>
    <link type="text/css" rel="stylesheet" href="/css/fontawesome.min.css"  media="screen,projection"/>
    <link type="text/css" rel="stylesheet" href="/css/style2.css"  media="screen,projection"/>
    <meta name="description" content="Learn the latest technologies with our hands-on labs">
    <!-- start Mixpanel --><script type="text/javascript">(function(f,b){if(!b.__SV){var a,e,i,g;window.mixpanel=b;b._i=[];b.init=function(a,e,d){function f(b,h){var a=h.split(".");2==a.length&&(b=b[a[0]],h=a[1]);b[h]=function(){b.push([h].concat(Array.prototype.slice.call(arguments,0)))}}var c=b;"undefined"!==typeof d?c=b[d]=[]:d="mixpanel";c.people=c.people||[];c.toString=function(b){var a="mixpanel";"mixpanel"!==d&&(a+="."+d);b||(a+=" (stub)");return a};c.people.toString=function(){return c.toString(1)+".people (stub)"};i="disable track track_pageview track_links track_forms register register_once alias unregister identify name_tag set_config people.set people.set_once people.increment people.append people.track_charge people.clear_charges people.delete_user".split(" ");
    for(g=0;g<i.length;g++)f(c,i[g]);b._i.push([a,e,d])};b.__SV=1.2;a=f.createElement("script");a.type="text/javascript";a.async=!0;a.src="//cdn.mxpnl.com/libs/mixpanel-2.2.min.js";e=f.getElementsByTagName("script")[0];e.parentNode.insertBefore(a,e)}})(document,window.mixpanel||[]);
    mixpanel.init("5574553b9aa0851a3c9fa0fc4cd101df");</script><!-- end Mixpanel -->
    <script>
      (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
      (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
      m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
      })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
    
      ga('create', 'UA-56533756-2', 'katacoda.com');
      ga('send', 'pageview');
    </script>
    <meta property="og:image" content="https://www.katacoda.com/images/apple-touch-icon-152x152.png"/>
    <link rel="apple-touch-icon" sizes="57x57" href="/images/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/images/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/images/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/images/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/images/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/images/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/images/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/images/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/images/apple-touch-icon-180x180.png">
    <link rel="icon" type="image/png" href="/images/favicon-32x32.png" sizes="32x32">
    <link rel="icon" type="image/png" href="/images/android-chrome-192x192.png" sizes="192x192">
    <link rel="icon" type="image/png" href="/images/favicon-96x96.png" sizes="96x96">
    <link rel="icon" type="image/png" href="/images/favicon-16x16.png" sizes="16x16">
    <link rel="manifest" href="/images/manifest.json">
    <link rel="shortcut icon" href="/images/favicon.ico">
    <meta name="msapplication-TileColor" content="#0176c0">
    <meta name="msapplication-TileImage" content="/images/mstile-144x144.png">
    <meta name="msapplication-config" content="/images/browserconfig.xml">
    <meta name="theme-color" content="#0176c0">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:site" content="@teamKatacoda" />
    <meta name="twitter:creator" content="@teamKatacoda" />
    <meta name="twitter:title" content="Learn Git Version Control using Interactive Browser-Based Labs | Katacoda" />
    <meta name="twitter:description" content="Learn the latest technologies with our hands-on labs" />
    <meta name="twitter:image" content="https://www.katacoda.com/images/twitter-card.png" />
    <meta property="og:url" content="/courses/git" />
    <meta property="og:title" content="Learn Git Version Control using Interactive Browser-Based Labs | Katacoda" />
    <meta property="og:description" content="Learn the latest technologies with our hands-on labs" />
    <meta property="og:image" content="https://www.katacoda.com/images/apple-touch-icon-152x152.png" />
    <script type="application/ld+json">
    {
      "@context": "http://schema.org",
      "@type": "Organization",
      "name": "Katacoda",
      "description": "Interactive Learning and Training Platform for Software Engineers",
      "url": "https://www.katacoda.com",
      "logo": "https://www.katacoda.com/images/logo-head.png",
      "sameAs": [
        "https://www.facebook.com/katacoda",
        "https://twitter.com/teamKatacoda",
        "https://github.com/katacoda"
      ]
    }
    </script>
  </head>

  <body class="row">

    <script type="text/javascript" src="/js/jquery-2.1.1.min.js"></script>

    <div id="confirmation-top"></div>

    <section id="course-pathway" class="color-bar-layout">
  <nav>
    <a href="/" id="logo" class="brand-logo">
      <img src="/images/logo-white.png" alt="Katacoda Logo"/>
      <h1>Katacoda <small>Interactive Learning and Training Platform for Software Engineers</small></h1>
    </a>
    <a href="#" style="font-size: 150%;" data-target="nav-mobile" class="top-nav sidenav-trigger waves-effect waves-light circle hide-on-large-only">
      <i class="fa fa-bars"></i>
    </a>
    <ul id="nav-mobile" class="sidenav sidenav-fixed hide-on-large-only" style="overflow: auto;">
      <li><a href="/learn">Learn</a></li>
      <li><a href="/create">Create</a></li>
      <li><a href="/embed">Embed</a></li>
      <li><a href="/embed">For Vendors</a></li>
      <li><a href="/trainers">For Trainers</a></li>
      <li><a href="/teams">For Teams</a></li>
      <li><a href="/enterprise">For Enterprises</a></li>
      <li><a href="/search">Search</a></li>
          <li class=""><a href="/profile">Claim Your Profile</a></li>
        <li><a href="/logout">Log Out</a></li>
    </ul>
    
    <ul class="right hide-on-med-and-down">
      <li><a class="course-header-only" href="/">Katacoda Overview &amp; Solutions</a></li>
      <li><a class="hide-on-course" href="/learn">Learn</a></li>
      <li><a class="hide-on-course" href="/create">Create</a></li>
      <li><a class="hide-on-course" href="/embed">Embed</a></li>
      <li><a class="hide-on-course" href="/embed"><span class="header-extra-text">For</span> Vendors</a></li>
      <li><a class="hide-on-course" href="/trainers"><span class="header-extra-text">For</span> Trainers</a></li>
      <li><a class="hide-on-course" href="/teams"><span class="header-extra-text">For</span> Teams</a></li>
      <li><a class="hide-on-course" href="/enterprise"><span class="header-extra-text">For</span> Enterprises</a></li>
      <li><a href="/search">Search</a></li>
          <li class=""><a href="/profile">Claim Your Profile</a></li>
        <li><a href="/logout">Log Out</a></li>
    </ul>
  </nav>

  <div class="color-bar-heading">
    <h1>Learn Git Version Control using Interactive Browser-Based Scenarios</h1>
    <h3>By Ben Hall</h3>
    <h2>Solve real problems and enhance your skills with browser based hands on labs without any downloads or configuration</h2>
  </div>

  <section class="x row">
    <div class="panels col s12">
      <div class="col s12 hide-on-med-and-down" id="user-course-progress">
          <div class="row">
            <div class="col s8">
              <h2>Your Progress</h2>
            </div>
            <div class="col s4 text-right help-container hidden">
              <a class="help" href="/courses/git/help">Get help/feedback</a>
            </div>
          </div>
          <div class="row">
            <div class="col s2">
              <img src="/images/icons/default-avatar.png" alt="" />
            </div>
            <div class="col s10 metric-container">
              <div class="row">
                <div class="col s6 metric-header">
                  Scenarios Completed
                </div>
                <div class="col s3 metric-header">
                  Progress
                </div>
                <div class="col s3 metric-header">
                  Points
                </div>
              </div>
              <div class="row">
                <div class="col s6 metric">
                  <span class="done">4</span> of 9
                </div>
                <div class="col s3 metric">
                  45%
                </div>
                <div class="col s3 metric">
                  40
                </div>
              </div>
            </div>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 45%"></div>
          </div>
          <div class="social-share row">
            <div class=" col s4">
              <a class="social linkedin">
                <i class="fa fa-linkedin"></i>
                <div class="">Share</div>
              </a>
            </div>
            <div class="col s4">
              <a class="social twitter">
                <i class="fa fa-twitter"></i>
                <div class="">Share</div>
              </a>
            </div>
            <div class=" col s4">
              <a class="social facebook">
                <i class="fa fa-facebook"></i>
                <div class="">Share</div>
              </a>
            </div>
          </div>
            <a href="/courses/git/5" class="action start">Continue Course</a>
      </div>
        <div class="panel scenario git completed col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 1 - Committing Files</h4>
            <p>
              Learn how to initalise a repository and start committing files.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action repeat" href="/courses/git/1">
                <i class="fa fa-sync"></i>
                Repeat Scenario
              </a>
        </div>
        <div class="panel scenario git completed col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 2 - Committing Changes</h4>
            <p>
              Learn how to compare and commit changes.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action repeat" href="/courses/git/2">
                <i class="fa fa-sync"></i>
                Repeat Scenario
              </a>
        </div>
        <div class="panel scenario git completed col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 3 - Working Remotely</h4>
            <p>
              Learn how to share your changes with others and access other people&#x27;s changes.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action repeat" href="/courses/git/3">
                <i class="fa fa-sync"></i>
                Repeat Scenario
              </a>
        </div>
        <div class="panel scenario git completed col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 4 - Undoing Changes</h4>
            <p>
              Learn how to undo changes when required.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action repeat" href="/courses/git/4">
                <i class="fa fa-sync"></i>
                Repeat Scenario
              </a>
        </div>
        <div class="panel scenario git  col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 5 - Fixing Merge Conflicts</h4>
            <p>
              Learn how to fix merge conflicts then they occur.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action start" href="/courses/git/5" title="Scenario 5 - Fixing Merge Conflicts">Start Scenario</a>
        </div>
        <div class="panel scenario git  col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 6 - Experiments Using Branches</h4>
            <p>
              Learn how to create branches of master for experimenting and prototyping ideas.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action start" href="/courses/git/6" title="Scenario 6 - Experiments Using Branches">Start Scenario</a>
        </div>
        <div class="panel scenario git  col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 7 - Finding Bugs</h4>
            <p>
              Learn how to find commits related to bugs and issues with code.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action start" href="/courses/git/7" title="Scenario 7 - Finding Bugs">Start Scenario</a>
        </div>
        <div class="panel scenario git  col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 8 - Being Picky With Git</h4>
            <p>
              Learn how to pick certain commits and changes from other repositories.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action start" href="/courses/git/10" title="Scenario 8 - Being Picky With Git">Start Scenario</a>
        </div>
        <div class="panel scenario git  col s3">
          <i class="fa fa-github"></i>
          <div class="content">
            <h4>Scenario 9 - Re-writing History</h4>
            <p>
              Learn how to re-write history when required.
            </p>
          </div>
          <div class="progress">
            <div class="determinate" style="width: 100%"></div>
          </div>
          <i class="fa fa-check"></i>
              <a class="action start" href="/courses/git/11" title="Scenario 9 - Re-writing History">Start Scenario</a>
        </div>
        <div class="panel docker playground col s3">
          <i class="fa fa-github"></i>
          <img class="cloud" src="/images/icons/cloud.png" alt="Interactive Learning Playgrounds" />
          <h4>Playground</h4>
          <p>
            Use Git in a safe playground environment
          </p>
          <a class="action start" href="/courses/git/playground">
            Explore Playground
          </a>
        </div>
    </div>
  </section>
</section>

  <section id="recommended" class="blue-rect-background row x">
    <div class="">
      <h2>Related courses you might enjoy</h2>
      <div class="panels">
          <div class="panel kubernetes col s3">
            <i class="fa fa-kubernetes"></i>
            <span class="count">14 SCENARIOS</span>
            <h4>Learn Kubernetes</h4>
            <p>
              Learn how to get started with Kubernetes
            </p>
            <a class="action start" href="/courses/kubernetes" title="Learn Kubernetes">
              Start Course
            </a>
          </div>
          <div class="panel docker-security col s3">
            <i class="fa fa-docker"></i>
            <span class="count">10 SCENARIOS</span>
            <h4>Docker Security</h4>
            <p>
              Learn how to secure Docker Containers
            </p>
            <a class="action start" href="/courses/docker-security" title="Docker Security">
              Start Course
            </a>
          </div>
          <div class="panel docker-production col s3">
            <i class="fa fa-docker"></i>
            <span class="count">5 SCENARIOS</span>
            <h4>Docker in Production</h4>
            <p>
              Learn the best practices of deploying Docker into Production
            </p>
            <a class="action start" href="/courses/docker-production" title="Docker in Production">
              Start Course
            </a>
          </div>
          <div class="panel git col s3">
            <i class="fa fa-github"></i>
            <span class="count">9 SCENARIOS</span>
            <h4>Git Version Control</h4>
            <p>
              Learn how to be effective with Git version control
            </p>
            <a class="action start" href="/courses/git" title="Git Version Control">
              Start Course
            </a>
          </div>
      </div>
    </div>
  </section>


<footer>
  <p class="left">
    Copyright &copy; 2016-2019, Ocelot Uproar Ltd. All rights reserved.
  </p>
  <p class="text-right">
    <a href="/docs">Documentation</a> | <a href="/blog">Blog</a> | <a href="/press-kit">Press Kit</a> | <a href="/careers">Careers</a> | <a href="/legal">Legal</a> | <a href="http://twitter.com/teamKatacoda" target="_blank" rel="noreferrer">@teamKatacoda</a> | <a href="/cdn-cgi/l/email-protection#296f465c474d4c5b5a6962485d484a464d48074a4644"><span class="__cf_email__" data-cfemail="0e48617b606a6b7c7d4e456f7a6f6d616a6f206d6163">[email&#160;protected]</span></a>
  </p>
</footer>


    <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script type="text/javascript" src="/js/vendor/webfont.js"></script>
    <script type="text/javascript">
      WebFont.load({
        google: {
          families: ['Open Sans']
        },
        custom: {
          families: ['franklingoturwtotbooregular']
        }
      });
    </script>


    <script type="text/javascript" src="/js/materialize.min.js"></script>
    <script type="text/javascript" src="/js/application.js"></script>

    <script type="text/javascript">

      var app;
      $(document).ready(function() {
        if (window.trackJs) {
          trackJs.addMetadata("host", 'cykoria01');
          trackJs.addMetadata("deployment", 'katacoda');
        }
        app = new App();
        app.init();
        app.stripe = {
          publish_key: 'pk_live_fGt75qCtGfvQn73mpo5YCwca'
        }
      });

      window._csrf = '';
      window.on_application_load = function(app) {
          mixpanel.identify("skunkel@umich.edu");
          mixpanel.people.set({
            "$email": "skunkel@umich.edu",
            "$created": "2019-01-27T23:20:21.127Z",
            "$last_login": new Date(),
            "$name": 'skunkel@umich.edu',
          });
          app.set_user({
            "id": "",
            "username": "4jl0jm",
            "public_username": "4jl0jm",
            "email": "skunkel@umich.edu",
            "created_at": "2019-01-27T23:20:21.127Z",
            "name": ''
          });
      }

    </script>

  </body>
</html>


```

## Question 2
``` 2
git diff
```

## Question 3
``` 3
commit 3d6ffedf2858ccc9eb6eb0e4516d3e13f004a571
Author: skunkel <skunkel@umich.edu>
Date:   Sun Jan 27 18:44:14 2019 -0500

    commit

diff --git a/Binary_tree.cpp b/Binary_tree.cpp
new file mode 100644
index 0000000..e725b5f
--- /dev/null
+++ b/Binary_tree.cpp
@@ -0,0 +1,496 @@
+/*
+ * Binary_tree.h
+ *
+ *  Created on: Feb 2, 2014
+ *      Author: James Perretta
+ *       Email: jameslp@umich.edu
+ */
+
+#include "Binary_tree.h"
+
+#include <cassert>
+
+#include <iostream>
+#include <iomanip>
+#include <string>
+#include <sstream>
+#include <cmath> // pow
+#include <set>
+#include <stack> // used in get_max_elt_width()
+
+using std::cout;
+using std::endl;
+
+using std::string;
+using std::ostream;
+using std::ostringstream;
+using std::setw;
+using std::left;
```

## Question 4
``` 4
Git opened a vi text editor.
```

## Question 5
``` 5
Git opened an emacs text editor.
```

## Question 6
``` 6
The -nw flag allows you to type in the text editor. When there is no -nw flag, you cannot type normally in the editor and must use type preset messages (y, n, ?).
```

## Question 7
``` 7
The value that you set GIT_EDITOR to takes priority over the value you set EDITOR to.
```