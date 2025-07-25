---
layout: essay
type: essay
title: "My Reflection on UI: I like it"
# All dates must be YYYY-MM-DD format!
date: 2025-07-01
published: true
labels:
  - UI Frameworks
  - Reflection
  - ICS314
---

<img class="img-fluid" src="../img/software-engineering.png">

# Beyond Web Apps: What Software Engineering Really Taught Me

When I signed up for this course, I thought I was going to learn how to build websites. And sure, I did learn that - but what caught me off guard was discovering that the real lessons were much bigger than any specific technology. The web applications we built were just the vehicle for learning fundamental software engineering principles that apply way beyond the world of HTML, CSS, and JavaScript. People like me might ask: why does this matter if I'm not planning to be a web developer? 

I've also learned that, "There's no such thing as a stupid question." There are definitely aspects of software engineering that seem pointless at first, and along with that, usually unhelpful resistance from students. Though we all might be guilty of being callous and dismissing these practices as busy work, there are steps we can take to understand that software engineering is fundamentally about systematic approaches to managing complexity.

Think of it like learning to cook. You might start by making simple pasta dishes, but what you're really learning are fundamental techniques - knife skills, seasoning, timing - that work whether you're making Italian, Thai, or Mexican food. The pasta was just the vehicle for learning those deeper principles.


## Configuration Management: More Than Just Git Commands

Configuration management refers to the systematic process of handling changes to a system while maintaining its integrity over time. In our course, this meant learning Git for version control, setting up consistent development environments, and managing different configurations for development versus production. At first, all the Git commands felt like busy work - why couldn't we just save our files like normal?

My first week with Git was neither terrible nor good. There were so many commands to remember: git add, git commit, git push, git pull, and don't get me started on merge conflicts.

```
git add .
git commit -m "fixed stuff" // terrible commit message
```

This was true for most of my early commits, and I had to learn to write meaningful commit messages that actually described what I changed. Additionally, there were instances where I'd accidentally commit files I didn't mean to, which was annoying.

While the heading of our file naming could have been better, it did convey what we were trying to figure out. Usually something as brief as "Fixing " is what other team members would look for when searching through project folders, making it easily found. But the real problem was that it wasn't just a file - we had multiple versions with no clear indication of what each person had done or which one represented our current progress.

Wonder how to keep track of changes across multiple people without everything turning into chaos? Or make sure everyone is working with the same version of important files? Configuration management answers these questions. It's not just about Git commands; it's a flexible, proven approach to managing shared work.

For example:

```
Issue #23: Add user login functionality
Goal: Implement secure user authentication system

Current situation: Users can access the application but cannot save preferences 
or access personalized content because we lack user accounts.

Requirements:
- Users should be able to create accounts with email/password
- Login sessions should persist across browser sessions
- Password reset functionality required
- Integration with existing user profile system

Acceptance criteria:
- Registration form validates email format and password strength
- Login redirects to user dashboard upon success
- "Remember me" option extends session to 30 days
- Password reset sends email with secure token

Technical constraints:
- Must use existing PostgreSQL database
- Frontend built with React, backend with Node.js
```

This clearly states the objective, provides context about the current situation, and includes specific acceptance criteria. The team can understand exactly what needs to be built and how to measure success.

As our projects grew more complex, the value became clear. I started writing my files and objectives with more details and tried to covey it in "one language." 

Overall, agile project management might be hard and confusing at first, but then your team starts working more efficiently, making it easier to coordinate and understand what everyone is working on. Plus, it gives you a shared language, so team members can chat about complex project status using simple, widely understood terms.

## The Real Lesson: Smart Communication for Complex Problems

What strikes me most about these software engineering concepts is that they're fundamentally about communication - how to ask the right questions, provide the right information, and collaborate effectively on complex problems. When we rely on others' generosity and expertise to provide answers to our questions, it should hold that the way we structure our work should be one that leads to efficient and effective collaboration that not only benefits us, but also the people we work with and others who might tackle similar challenges in the future.

Whether you're managing thousands of lines of code or coordinating a team of people working toward a common goal, the underlying challenges are similar: How do you maintain consistency? How do you track changes without losing your mind? How do you break overwhelming problems into manageable pieces?

A "smart" approach to any collaborative project isn't just about being articulate; it's about providing the necessary context, demonstrating prior effort, and pinpointing the core issue in a way that helps others provide precise solutions. This applies whether you're asking for help on Stack Overflow, writing commit messages, or creating project issues.

The web applications we built served as a convenient way to practice these principles, but the specific technologies we used will probably be obsolete in a few years. Bootstrap will be replaced by something else, JavaScript frameworks will evolve, and new tools will emerge. But the fundamental approaches to managing complexity and facilitating collaboration will remain relevant whether I end up building mobile apps, analyzing data, managing projects, or working in completely different fields.

## Conclusion

When we rely on systematic approaches to manage complex projects, it should hold that the methods we use should be ones that lead to efficient and effective collaboration that benefits everyone involved. Thus, if you have a complex project... make your approach a smart one! Using software engineering principles may not always get you the perfect outcome, but applying them in a way that will make others want to work with you will increase the success of finding good solutions and make it a positive experience on all sides.

Bottom line: software engineering principles are essential for tackling complex projects. They turn chaotic collaboration into really cool and awesome systematic processes. By applying configuration management and agile project management, you can create robust, easy-to-maintain, and adaptable workflows just like a master chef who consistently creates well-structured and truly memorable meals.

This course taught me that software engineering isn't really about programming - it's about developing systematic approaches to building complex things with other people. The biggest surprise was realizing that the most valuable skills I learned weren't technical - they were communication and organizational skills. Learning to break down complex problems, manage changes systematically, ask smart questions, and work effectively with others are skills that will serve me well regardless of what I end up building or where my career takes me.
