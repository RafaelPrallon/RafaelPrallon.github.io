---
layout: post
title:  "Remaking Project Monitor: Step one - Seeing what's not good now"
date:   2017-08-26 20:13 -0300
categories: projects energy-monitoring
comments: true
---
During college, I've made a web system in rails for online exibition of measurement data of energy meters. But, since both Ruby language and Ruby on Rails were quite new things for me, the project itself ended up with some issues. So I've decided to remake it once I've got more experienced in rails development. I believe that now that I'm ready, so follow me through this process of remaking an old project.

In this first post I'll go through what can be improved over the previous code and why they should be changed.

Issues detected so far:
- The code isn't clean or organized: I can not highlight enough on how important is a clean and organized code. It makes updates to the code easier and makes it simpler to find possible errors
- Did not follow many of Ruby Development's good practices: Some of the Rails principles like DRY were not followed during the first version of the project, contributing to the previous issue
- The code wasn't developed following an test first aproach, what made debbuging harder and you may end up writing more code than necessary to implement a feature
- the layouts could look better: At the time I wasn't able to extract most of the potencial use of bootstrap so i ended up with some visual issues like the font ending up being to small at mobile and the overall theme of the app coud be improved

Possible improvements:
Since the code is being rewritten, we can take the opportunity to add some functions and updates like:
- Make it cloud ready since the beggining
- The original one where made in rails 4.2, we can update it to rails 5.1
- Maybe make use of ionic alongside rails to make it able to be converted to an mobile app easily.
- Adds RSpec and Capybara in order to implement BDD

The repo for the original code is right <a href = "https://github.com/RafaelPrallon/rails_pf_sqlite"> here</a>

See anything more that could be added to the project? Disagree on any of the improvements proposed? Add your suggestions in the comments bellow.