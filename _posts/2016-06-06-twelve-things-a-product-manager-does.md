---
title: Twelve things a product manager does
description: The twelve most important things a product manager can do on any given day
---

When I was first considering making the move to product management, I read [a lot](https://medium.com/@joshelman/a-product-managers-job-63c09a43d0ec#.t7puifka7) [of posts](https://medium.com/@matbalez/product-manager-you-are-664d83ee702e#.6054jkko8) [about what](https://medium.com/@bfgmartin/what-is-a-product-manager-ce0efdcf114c#.nfocpyput) [a product](https://medium.com/@irishbryan/product-managers-are-apes-21f25828dcb7#.ujgo9swh6) [manager does](https://medium.com/@noah_weiss/50-articles-and-books-that-will-make-you-a-great-product-manager-aad5babee2f7#.1t1kwhhly). Many of these posts, books, and resources were helpful to understanding what role a product manager plays within the larger organization, or what common traits great product managers share, but given the diversity of the term within the industry, it was hard to get a sense for what a product manager's typical day looked like, at least if there was such a thing at GitHub.

I've been keeping notes on everything I've done as a product manager over the past six months, and bucketizing things a bit (as we product managers say). Here's my list of the twelve most important things a product manager can do on any given day:

### 1. Being the one not allowed to have excuses

First and foremost, as a product manager, you are ultimately responsible for the product's success and held accountable for anything even remotely resembling failure, no matter the true cause. *Marketing material didn't strike the right tone? Technology didn't pan out as expected? Budget priorities shifted? Competitor moved faster? Personalities clashed?* Regardless of where the blame *should* lie, when all's said and done, you're the one people are going to look to. This can be a scary arrangement at first, but it also gives you the political capital to make tough decisions and assume responsibility on behalf of those you depend on. Above all else, your job is to ensure a successful product.

### 2. Team captain

Depending on how your organization is structured, there's a good chance that teams — the internal groupings that do the organization's day-to-day work — and products — the user-facing things that you actually exist to build — don't align. A product might be built by an engineering team, tested by a QA team, documented by a documentation team, and supported by a support team, among many, many other teams. As a product manager, you're the captain of the (often imaginary) cross-functional team that ties all those disparate efforts together. Part quarterback, part social worker, part organizational sherpa, and part matchmaker, your job is to do whatever it takes to ensure players do their best on and off the field.

### 3. User advocate

Engineers love solving tough engineering challenges. Logically inconsistent, philosophically impure, or technically inefficient code is like nails on a chalkboard to us. We'd like nothing better than to spend weeks figuring out the most elegant way to refactor it, and then do it all again six months later. The problem is, that month-long project is going to deliver little to no end-user value. *Can we make the feedback more context aware, even if it's more work for us in the long run? Can we make this process more self-serve for users? Can we cut this otherwise-cool feature entirely to reduce the cognitive burden?* While, it's tempting to optimize ships from the maintainer's point of view, as a product manager, your job is to serve as what is often the sole voice of the user internally, advocating for user centricity in everything you do, practically and philosophically, and to ensure you're absorbing your product's complexity on your users' behalf.

### 4. Prioritize and sequence

At some point you'll realize there's always going to be more to do than time to do it, and that that's perfectly okay. Given a solid team and sufficient community, there's going to be no shortage of ideas, both internal and external. Add to that, the fact that given the right talent and time, any technical challenge is surmountable, and you'll find yourself presented with near infinite possibilities. Your job as a product manager is to prioritize those tasks, floating highly-visible bugs and those features that target your core use case to the top of the list on the one hand, and also to sequence tasks, to knock out the low-effort, high-impact features first, and then schedule the rest in an order that makes sense on the other. If you've ever played any real-time strategy game, you know how important it is to properly sequence early investments alongside resource growth. Product management is no different.

### 5. Communicate, coordinate, and facilitate

Your team should focus on shipping. You should focus on all the meta-work necessary to create the space that allows that to happen. That means memorializing synchronous meetings, shuttling information to other affected teams, and coordinating cross-team efforts (and overcoming any organizational friction that may arise as a result). At GitHub we have the idea of [servant leadership](https://en.wikipedia.org/wiki/Servant_leadership). As a product manager, your job is to provide your team with the all political, yak-shaving, and unblocking air cover necessary so that they can focus exclusively on shipping. Make sure other teams know what you're up to, are able to opt-in to additional context if they'd like, and harmonize any supporting or parallel efforts across the organization. You should be the most organized person on your team, and be able to tell, at any given moment, exactly what needs to be done to get the feature shipped (and to make sure that is exactly what happens).

### 6. Solve for what the customer wants, not what they're asking for

Your customers are experts at using your product. They're not necessarily experts at building it. It's all too easy to [optimize for the squeakiest wheels](http://ben.balter.com/2016/03/08/optimizing-for-power-users-and-edge-cases/), but those you hear from the most aren't necessarily your target audience. As a product manager, your job is to solve for the customer's underlying needs, not to respond to feature requests *a la carte*. For one, you have the privilege of a birds-eye view — you don't just see one use case, but all of them. For another, you enjoy the benefit of data, both historical and experimental. Most importantly, you should have a vision for what the product can, and should be doing, even if that's not what it's doing that today. Your customer wants [a 1/4" hole](https://strategyn.com/jobs-to-be-done/). They may ask for a bigger drill bit or a stronger motor, but the right solution might ultimately be an adhesive hook.

### 7. Ensure you ship v0.1 not v1.0

Coming up with the vision for the 1.0 version of any feature is the easy part. Giving into the temptation to forgo shipping until it's absolutely perfect is even easier. The challenge lies in breaking that feature into a minimal 0.1 that you can immediately expose to users, and following up with subsequent ships that improve upon the first. Not only do users begin getting some of the feature's value early on, but rather than spending six months potentially heading in the wrong direction, you can see how its used in the wild, and can adjust your plans accordingly. Incremental ships also keep the number of moving parts to a minimum, and help avoid "flip a giant switch"-style deploys that subject users to large swaths of untested code.

### 8. Don't confuse urgent with important

Throughout a product's lifecycle, you'll generally see two types of tasks, those that are urgent, and those that are important. Urgent tasks naturally flow in every day. They're the constant barrage of "the sky is falling" requests that are already impacting end users. Important tasks, on the other hand, are often more subtle, often only emerge when you specifically set aside time to discover them, and can often have the highest end-user impact. Your job as a product manager is to distinguish between the urgent and the important, and to allocate time accordingly. Whether it's 60/40, 50/50, or 40/60 may depend on the product, but absent purposeful intervention, product teams will almost always focus entirely on the short term and the urgent, neglecting your product's most important, longest lasting work.

### 9. Don't confuse measurable with important

Organizations have a bad habit of confusing what's measurable or visible with what's important, and neglecting the immeasurable as a result. Just because something suddenly comes into focus, doesn't mean that that thing deserves your immediate focus. Gaining the ability to track page views for example, (and seeing how few there are) doesn't mean you should drop everything and shift to maximizing eyeballs. Your job as a product manager is to think purposefully about what metrics you should be collecting, what can't be quantified, and what you should be optimizing for, both today, and in the long run.

### 10. Capture every idea in an issue backlog

Ideas come up. There are the ideas that naturally arise during your weekly checkin or while grabbing a cup of coffee. There are the support tickets you don't have a good answer for. There are the next steps uncovered during your last blameless post mortem. Whatever the source, open an issue, open lots of them, and encourage other to do the same. Issues are cheap. They're free to open, easy to close, and provide a permanent record of why the organization chose or chose not to do a particular thing. They track progress, centralize decision making, and cross-link related ideas. As a product manager, your job is to ensure those never-ending ideas get captured in a never-ending issue back log, fleshed out, updated, and closed, one way or another. Your job is also to own that backlog, being at least superficially familiar with each issue, cross referencing prior art, and surfacing related discussions as they become relevant.

### 11. Research and strategic thinking

It's easy enough to take the top feature off the backlog, grind away for a few weeks, ship, wash, and repeat. Leave that to your team. Your job is to spend at least one day a week (yep, that's 20% of your time), taking a step back from the day-to-day and focusing on the month-to-month and the year-to-year — to think through the tough non-technical problems you're product's trying to solve. *Who's your target audience? How many people actually use that feature? How are they using it? Can you remove it? Can you fold two features into one? What does the user experience look like in a month? A year? Three? Five?* You need to be the one that knows the product best, not just today, but also five years from now.

### 12. Keep up with industry trends and customer demand

You are responsible for keeping the lights on, for keeping the servers up, the trains running on time, and the (existing) customers happy. But that's the showing-up-to-work-on-time of product management. If [the Innovator's Dilemma](https://en.wikipedia.org/wiki/The_Innovator%27s_Dilemma) teaches us anything, it's that your job isn't to ship the product that customers want today, but to constantly be preparing to ship the product that your customers will want six months, a year, or even a few years from now. That means not only trudging through all the Slack bot announcements on Hacker News, Product Hunt, and TechCrunch to be able to plot the industry's trajectory, but also being your organizations's foremost expert on your users, the problem space, and their needs. You should seek to cultivate an encyclopedic knowledge of everything that affects your product, inside the organization and out.

That's my list of the top twelve things I've done over the past six months as a product manager, but there's obviously, much, much more. Does that match your experience? Something I left out? I'd love to hear your thoughts in the comments below.