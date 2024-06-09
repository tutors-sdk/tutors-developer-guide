---
icon:
  type: flat-color-icons:entering-heaven-alive
---

Introduction

What is tutors

[[toc]]

Tutors is a collection of open source components and services supporting the creation of transformative learning experiences using open web standards. It consists of two key components:

- *Generator:*  transforms a [folder of learning content](https://github.com/tutors-sdk/tutors-reference-course)  into a Tutors course

- *Reader*: presents a Tutors course as an intuitive, discoverable and attractive [Web experience](https://tutors.dev/course/reference-course)

These components are [developed in the open](https://github.com/tutors-sdk/tutors) by an active and friendly community, based on a clear [set of values](https://tutors.dev/course/tutors-reference-manual#tutors-values).

Please see the [Tutors Reference Manual](https://tutors.dev/course/tutors-reference-manual) for guidance on creating and publishing tutors courses.

### Example Tutors Courses

A suite of open source courses that focus on web development:

- [Full Stack Development](https://github.com/wit-hdip-comp-sci-2023/full-stack-1)

This is a selected Course Gallery:

- [Gallery of Tutors Courses](https://tutors.dev/gallery)

Some courses of interest:

- [Higher Diploma in Computer Science Portal](https://tutors.dev/course/wit-hdip-comp-sci-showcase)
- [Full Stack Development](https://tutors.dev/course/full-stack-web-dev-oth-2022)
- [Data Analytics](https://tutors.dev/course/data-analytics-essentials)
- [Reference Course](https://tutors.dev/course/reference-course)
- [Higher Diploma in Computer Science at SETU: 2020-2022](https://tutors.dev/course/wit-hdip-comp-sci-2020)
- [Classic Design Patterns](https://tutors.dev/course/classic-design-patterns)
- [Agile Software Development](https://tutors.dev/course/agile-2023)
- [Technologische Fähigkeiten](https://tutors.dev/course/zusatzstudium-digital-skills-semester1)

Note: Some courses will request you authenticate via github for access.

## The Tutors Reader

The Tutors Reader is a SvelteKit application which presents a tutors module in an attractive, intuitive and discoverable user experience. The application is build from a single repository:

- https://github.com/tutors-sdk/tutors


### Rebuilding the Reader
Make sure you have Node 18 + installed, and start by cloning this repo:

~~~bash
git clone https://github.com/tutors-sdk/tutors.git
~~~

Open a shell and change into the project folder and run `npm install`...

~~~bash
cd tutors
npm install
~~~

Then copy the file `.env.example` to `.env`

Now to start the app you can run this command from the root:

~~~bash
npm run dev
~~~

This should launch the application:

~~~bash
  VITE v5.0.12  ready in 1069 ms

  ➜  Local:   http://localhost:3000/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
~~~

Now the app is up and running and you can browse to it by opening the <a href="http://localhost:3000/">local location</a> in your browser.

The Tutors reader relies on a segment of the url to locate the course to display. Any of the samples below can be 'read' with an appropriate url segments appended to the local url you now have running. So for instance:

- <https://tutors.dev/course/reference-course>

... can be loaded locally by:

- <http://localhost:3000/course/reference-course>

(Note the port number 3000 may vary - see the launch console)

The 'source' for the above course is here:

- https://github.com/tutors-sdk/tutors-reference-course

You could try any of the other sample courses below. For example this course:

- https://tutors.dev/course/full-stack-1-2023

can be opened by this local reader like this:

- https://localhost:3000/course/full-stack-1-2023

## Deploying the Reader

# Designing a new Theme

## The Tutors Generators

