# Introduction to DevSecOps · Midterm · Option B: ship a change

**40 points.** No step-by-step instructions. You may use the course site, your notes and your repository.

## The goal

Your full name appears on the home page of your site, under the logo, instead of
“A place to share your knowledge.” The robot puts it there.

## The rules

1. The change travels the whole path: a branch, a pull request, green checks, a merge into `main`, and a release started by the pipeline.
2. Get the server and the pipeline ready any way you need. After the merge, do not touch the server by hand: no copying files, no starting or stopping anything.
3. The application runs in containers, from the images the robot built for the merge commit.
4. No secret appears in the repository, in the pull request, in the logs of a run or in your email.

## Done when

1. `https://YOUR-NAME` shows your name under the logo.
2. The run on `main` for the merge commit is green, and that run released it.
3. The API on your server reports the merge commit as the version it runs.
4. You explain to the instructor, step by step, what happens between your merge and the new text on the site, and where the secrets live.

## Send an email

To: [dastan.kozhomuratov@college.edu.kg](mailto:dastan.kozhomuratov@college.edu.kg?subject=Midterm%20Option%20B)

Subject: `Midterm Option B · YOUR FULL NAME`

In the email:

- your full name and group;
- the link to the pull request;
- the link to the green run on `main`;
- the address of your site;
- the merge commit SHA, and how the API on your server reports it (paste the output).

Then raise your hand for step 4.
