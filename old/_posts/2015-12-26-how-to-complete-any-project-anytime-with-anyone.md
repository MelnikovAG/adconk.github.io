---
layout: post
title: "How to Complete Any Project, Anytime, with Anyone"
description: "Our Startup Migration Story from Braintree to Stripe"
modified: 2015-12-26
tags: [stripe, braintree, payments, web apps, ruby on rails, fitness technology]
comments: true
---

### Our Startup Migration Story from Braintree to Stripe

During the Fall of 2015, we at [Routeam](https://routeam.com) completed our payment processor migration from [Braintree](https://braintreepayments.com) to [Stripe Connect](https://stripe.com/connect).  I felt proud, I felt relieved, but most importantly, I felt empowered that I could accomplish bigger things with my teammates. The migration of 6 figure quarterly payments was a major hurdle for us.  
<br />
Our core project team consisted of three people: A sales expert, a finance expert, and a software engineer. In the early stages, the engineer struggled to comprehend a feature set and produce a delivery timeline, the finance expert struggled to communicate a payment flow design with the new processor, and the sales expert preferred to keep focus on warm prospects rather than being hands on. How did we pull it together?  
<br />
Three characteristics were key to our success:  

1. we had a common goal  
2. we made a routine time to sync up and address knowns and unknowns  
3. we completed all five stages in the emotional cycle of change  

### What is the Emotional Cycle of Change?

It's a model devised by Don Kelley and Daryl Conner in the '70s, that expresses what we typically experience when we take on a new project, from start to finish, or when we encounter failure in between.  
<br />
The stages are:  

1. Uninformed Optimism  
2. Informed Pessimism  
3. Hopeful Realism  
4. Informed Optimism  
5. Completion  

<a href="https://www.mindtools.com/pages/article/kelley-conner-cycle.htm">
<img src="/images/emotional-cycle-of-change.jpg" alt="Emotional Cycle of Change" />
</a>


### 'Uninformed Optimism' vs 'Informed Pessimism'

A lesson learned for me early in our project is that teammates are not always on the same stage at the same time.  Back in 2014, we made a decision to continue using our old payment processing model, knowing it would be a problem we would have to face in the future to permit us to scale.  This occurred because our teammates failed to set up a routine time to talk and hash out a common goal. The engineer’s informed pessimism fought the uninformed optimism of the sales expert and the finance expert.  We had a problem to solve, but we failed to work together and go as deep as it required to get where we wanted to go.

### Overcoming 'Informed Pessimism'

On our Fall 2015 project, we handled our 'Informed Pessimism' differently.  The engineer was vocal with objections and criticisms, while the sales expert and finance expert went quiet.  The sales and finance experts pulled away and became busy with other things during this stage, while the engineer had the expectation they would have more time to commit because all three had decided this was the most critical growth project for the business. During this stage, we faced our highest chance of failure. Our common goal and our regular sync-up kept us on the path of forward progress.

### 'Hopeful Realism' and Timelines

In our 'Hopeful Realism' stage, we could begin to see the finish line.  This was another substantial learning moment for me in contrast to my background within larger company teams.  I learned how emotional and organic the process can be with a small team consisting of diverse skills, starkly different mentalities, and varied weekly rhythms.  A team must analyze  to predict a timeline.  A team sometimes has to complete part of the project, or even complete a first iteration, so that a quality delivery can be estimated.  At this stage, you can definitely throw a scope and timeline out there with a high likelihood of success.  

### Comments on Braintree vs Stripe

___Support - Braintree wins___. Both teams were professional, but hands down, Braintree was more responsive, more willing to pick up the phone, and more concrete with its timelines on existing customer and credit card migrations. Stripe would only commit to a particular day for a migration, not a half day, and certainly not within a block of a few hours.  Also, Stripe was insistent about providing email support only.  
<br />
___Payment Processing - Tie___. If you’re looking for payment processing with tokenized credit card handling to offload most of your PCI compliance, Braintree or Stripe are on par.  Both have similar rates, great APIs, and stellar widgets that work well on web, hybrid, and native apps.  Also, for managing sub-merchants through your own UI, both providers work well.  
<br />
___Multi-Merchant - Stripe wins___. Our motivation for switching had a lot to do with Stripe Connect, and the ability to help our customers setup Standalone Merchant accounts quickly, without a lot of guidance.  Stripe is amazing at this.  Insight on the setup process can be found with this [article by Muno Creative](http://www.munocreative.com/nerd-notes/winvoice) for Ruby on Rails apps.  I only recommend this model if the added complexity solves a business requirement for you like it did for us.  In addition to setup, you are taking on a little bit of extra overhead on every [Stripe Connect API call](https://stripe.com/docs/connect/payments-fees).

### Concluding Thoughts

Looking ahead into 2016, I have a greater confidence in pulling together people with diverse backgrounds, experience, and skill sets to complete a project.  The odds of success are considerably higher when the people in the conversation truly want the outcome and set a common goal with a plan to connect at a regular times until completion.  Thank you to Agile and Lean UX for inspiration on this fundamental formula for project success.  I hope this thought process helps you in creating and succeeding on your next project.
