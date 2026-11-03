# QA Portfolio - Tegar

## About me

I'm Tegar, a fresh graduate in Informatics Engineering from Dian Nuswantoro University. Most of my past projects were full-stack web apps, so I know how things get built. Now I'm learning the other side of it: finding what breaks.

I don't have QA work experience yet, so this repo is where I practice in public. Everything here is something I tested myself on a practice app. Things I haven't done yet are marked as planned.

My goal is to work as a QA engineer, ideally in a bank or fintech company.

## What I'm practicing

- Manual testing: writing test cases, reporting bugs
- API testing with Postman
- Browser DevTools for checking errors
- Git and GitHub
- UI automation (Playwright or Selenium), starting after the API part

I also know Python, JavaScript and SQL from my web dev projects.

## Projects

| Project | What I did | App tested | Status |
| ------- | ---------- | ---------- | ------ |
| Grid Walker Game | Manual test cases + bug report | [Buggy Games](https://eviltester.github.io/TestingApp/games/buggygames/) | Done, found 1 bug |
| SauceDemo login and checkout | Manual test cases | [saucedemo.com](https://www.saucedemo.com) | In progress |
| Restful-Booker API | Postman requests, auth token, CRUD | [Restful-Booker](https://restful-booker.herokuapp.com/apidoc/index.html) | In progress |
| ParaBank | Banking flows (transfer, bill pay) | [ParaBank](https://parabank.parasoft.com) | Planned |
| UI automation + GitHub Actions | Run tests automatically on push | SauceDemo | Planned |

## Example: test case

| ID | Scenario | Steps | Expected | Actual | Status |
| -- | -------- | ----- | -------- | ------ | ------ |
| TC-GW-001 | Exit the grid after finishing a walk | 1. Click Generate<br>2. Click a cell in the left column<br>3. Walk to the right side<br>4. Click "Exit The Grid" | The game ends and shows a result | Nothing happens | Failed |

## Example: bug report

**BUG-001: "Exit The Grid" button does nothing after the walk is finished**

Steps:
1. Open the Grid Walker Game
2. Click Generate
3. Click a cell in the left column to start
4. Move through the grid to the right side
5. Click "Exit The Grid"

Expected: the game ends and I see if I won or lost.
Actual: nothing happens, the game just stays there.
Severity: High, because the game can't be finished.

Full report: [bug-reports/BUG-001_GridWalker_ExitButton.md](bug-reports/BUG-001_GridWalker_ExitButton.md)

## Folders

- `test-cases/` manual test cases
- `bug-reports/` bug reports
- `api-testing/` notes and Postman files
- `img/` screenshots

## Contact

- LinkedIn: add link here
- Email: add email here
