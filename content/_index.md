---
title: 'Support Engineer'
description: 'Eric Jinks'
date: 2018-11-22T07:54:57+10:00
featured_image: '/images/logomark-light.svg'
---



### List 5 things that are your most favorite to do and 5 things that are least favorite.

#### Favourite

* *Respond to 60+ support requests via email or chat every day*

    > Initially, I would find it challenging to respond to and resolve large volumes of support requests. However, I know that this is something I will be able to confidently manage as I become more experienced in this role.

* *Write and maintain documentation for our software and blog posts for our website.*

    > I would be excited to work on documentation and blog posts. Blogging is a skill that I am personally challenging myself to improve and spend time on.

* *Set up your own copy of several static site frameworks for debugging*

    > I enjoy experimenting with new static-site generators, I have even made a couple of my own ([Hyperstatic](https://github.com/Jinksi/hyperstatic) & [Netlify CMS + React Starter](https://github.com/Jinksi/netlify-cms-react-starter)).

* *Suggest and champion improvements to the product and workflow to your colleagues in and out of support*

    > Enhancing the team's workflow or Netlify's product would be something that I would take pride in and would bring me job satisfaction.

* *Debug a customer's build using a programming language and framework that you've never seen before*

    > I enjoy learning new things and problem-solving. Debugging is like a puzzle game, adding a new language or framework is like playing on hard-mode.

#### Least Favourite

* *Deliver a talk to many people you don't know at a conference or meetup*

    > Public speaking is a challenge that pushes me outside my comfort zone. I have delivered talks in the past and would like to grow my skills and confidence in this area.

* *Create video tutorials to help teach users a specific feature or use case*

    > I wanted to list this as 'favourite' as I would enjoy this task, but I am not overly-confident recording screencasts. Creating video tutorials is an area that I would like to learn and practice.
    
* *Help manage communications during a service outage*

    > I work well under pressure, however, this is a time when you'll be dealing with upset customers who demand answers. It is a stressful time for everyone involved.

* *Receive occasional phone calls requesting support from our highest-value customers*

    > I would be excited and confident to solve problems for our highest-value customers, however, this would be a challenging, high-pressure situation and would come with a little extra dose of urgency and imposter-syndrome.

* *Choose 5 least-favourite tasks*
    
    > This is by far my least-favourite task!

---

### What is your favorite thing about providing technical support?

My favourite part of providing technical support is learning by teaching. Communicating a concept or solution to someone in a way that is understandable brings a sense of achievement and confidence, both to the other person and yourself.

---

### What did you think of our service during the time you used it?

I have been using Netlify for around a year and I only have good things to say. This is largely due to the quality of documentation and support that you provide. Other developers that I have encouraged to use Netlify have had the same experience.

---

### Tell about how you made your site and why you chose the tools you did.  Briefly explain a challenge you experienced in setting up this site and how you solved it.

I would usually prefer to use a React-based tool such as Gatsby or my own project, Hyperstatic. I decided to use Hugo, as I know that it's one of the most popular generators and would be useful to learn. Hugo is so fast! The biggest challenge I came across was figuring out how the directory structure should be set up, which I overcame by reading the documentation and digging into the theme I installed.

---

### Could you give us a suggestion to improve this test or the job posting?

I found it difficult to choose 5 'least favourite' options from the first question. I ended up giving 5 options that I would find to be the 'most challenging', because most of these items would end up being 'favourite' items with a bit of practice and experience. My suggestion is to ask the applicant for 5 favourite items and 5 items they would find challenging, although this depends on what you are looking for.

---

### Provide a link to documentation for a technical/developer-focused product, that you think are well done, and briefly explain why you think they are well done.

A great example of good documentation is the [Lodash docs](https://lodash.com/docs/4.17.4). I can quickly find the information I am after using their intelligent search. They have human-readable descriptions of what each function does and their code examples cover multiple use-cases.

I also wanted to mention the [Digital Ocean Community](https://www.digitalocean.com/community/). It is a high-quality source of tutorials that I often turn to for help.

---

### Why do you think SSL/HTTPS is important?

SSL/HTTPS is an important security feature that can help to protect communications between your website and your users' browser from intruders. SSL/HTTPS is required to enable browser features such as [HTTP/2](https://http2.github.io/) and [Service Workers](https://developers.google.com/web/fundamentals/primers/service-workers/). Using SSL/HTTPS can also have the indirect benefit of making your site look more trustworthy to users.

---

### Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users

The first major hurdle when configuring DNS records is understanding what each DNS record is used for and which one should be modified to achieve the desired outcome.

Another challenge is understanding that updating DNS records will not be immediately visible to the end-user. Changes must be propagated across a global network of DNS servers, which can take an indeterminate length of time. The user's device and browser also cache DNS information, adding another common source of frustration.

---

### A customer writes in saying their “site won’t build”. Compose your best short (2-paragraph) customer-facing answer without any additional data, that could be useful in the generic case but would also lead to a customer providing a more actionable response.

Hi customer name,

That's not good! I'll have a look at your deploy logs and build settings to see if I can see what's going on. Which build tool or static site generator are you using to build the site? Are you able to provide a link to the site's git repository?

I'd encourage you to take a look at our build troubleshooting guide in our docs: https://www.netlify.com/docs/build-gotchas/.

Let me know if this helps.

Thanks,  
Eric

---

### Can you set up a redirect from “/netlify/anything” to https://www.google.com/search?q=anything ?

[/netlify/anything](/netlify/anything)

I achieved this using the following line in the `_redirects` file:

`/netlify/*  https://www.google.com/search?q=:splat`
