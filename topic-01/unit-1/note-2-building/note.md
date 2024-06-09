---
icon:
  type: flat-color-icons:flow-chart
---

Rebuilding Tutors

Install and rebuild the tutors reader

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
