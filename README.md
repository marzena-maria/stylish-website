# A Stylish Website

Build me something stylish!

## Installation

Run `npm install`

## Usage

- To run the live server, run `npm run serve`
- To run the SASS file watcher run `npm run scss-watch`
- For a one-time SASS/SCSS build, run `npm run scss-compile`
- For a one-time SASS linter check, run `npm run sass-lint`

## Preparing for your assignments

**Important!** Before working on these assignments, please make sure to create
a new branch with the name "solution" in the terminal;

`git checkout -b solution`

When you have finished making your changes, use the following command to mark all changed files
to be added to the next commit;

`git add .`

And then commit as follows;

`git commit -m "Your message"`

Replace the text _Your message_ with something a short summary of the changes you've made

It's good practise to separate your code changes into multiple commits,
for example - if you're building a website, you might want to have 1 commit for your header code,
one for your navigation code, etc.

## Submitting your assignments

Once you've finished your changes and you are ready to submit your work, you can push the changes
to the remote server via the following commands;

If you've already pushed before, you can simply use:

`git push`

If however you get an error, telling you the remote branch for "solution" does not exist, use the
following command:

`git push --set-upstream origin solution`

Once this is done, create a **Pull Request** from the `solution` branch to the `master` branch
via the GitHub interface.

## Assignments

[Mobile](./mobile-mockup.png)

[Tablet](./tablet-mockup.png)

[Desktop](./desktop-mockup.png)

Using the mockups available above, build a _Stylish Website_ using the resources available

+ Build a mobile, tablet and desktop version

+ Write your styles using SCSS

+ Use CSS Grid for the design of the site (where appropriate)

+ Use the following breakpoints:
    - Mobile (0 - 525px)
    - Tablet (526px - 1037px)
    - Desktop (1038px +)
    
+ For the arrow image, use the following element:
    - `<img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHhtbG5zOnhsaW5rPSdodHRwczovL3d3dy53My5vcmcvMTk5OS94bGluaycgd2lkdGg9JzM2cHgnIGhlaWdodD0nMjRweCcgdmlld0JveD0nMCAwIDM2IDI0JyB6b29tQW5kUGFuPSdkaXNhYmxlJz48c3R5bGU+bGluZSB7IHN0cm9rZTogI2ZmZmZmZjsgc3Ryb2tlLXdpZHRoOiAycHg7IH08L3N0eWxlPjxsaW5lIHgxPScwJyB5MT0nMTInIHgyPSczNCcgeTI9JzEyJyAvPjxsaW5lIHgxPScyNScgeTE9JzQnIHgyPSczNCcgeTI9JzEyLjUnIC8+PGxpbmUgeDE9JzI1JyB5MT0nMjAnIHgyPSczNCcgeTI9JzExLjUnIC8+PC9zdmc+" />`
    - The image is ~~included~~ embedded in the URL!
    
+ Fontawesome has already been setup for you. Use the following classes for the missing icons:
    - `class="fas fa-envelope"` - envelope
    - `class="fas fa-phone"` - phone
    - `class="fas fa-home"` - home
    - `class="fab fa-twitter"` - twitter
    - `class="fab fa-facebook-f"` - facebook
    - `class="fab fa-instagram"` - instagram
    - `class="fab fa-github"` - github
    - `class="fab fa-linkedin-in"` - linkedin
    