  # Little Shop | Group Project |
### Abstract:
- This project provides a robust API-driven backend designed to power a front-end application. It seamlessly integrates with an existing front end by delivering data through RESTful API endpoints and includes targeted adjustments to the front-end application to ensure smooth communication and functionality.
- Some Key features include API endpoints, Data Management, and error handling.

### Installation Instructions:
1. Fork repo
1. Clone forked repo and rename it `git clone <repo> <new name>` (Do not clone this into your BE repo. See note above.)
1. `cd` into cloned repo
1. Run `npm install`
1. Run `npm run dev` to start developing.
  1. You'll see in the terminal that the project has opened at "http://localhost:5173/"

### Preview of App:
![Little Shop Home Page](/Pics/Screenshot%202025-01-15%20at%2012.49.17 PM.png)

### Context:
- This project was a one-week collaborative effort by a team of four to build a functional application with both back-end and front-end components.
Work Process:
- Back-End: We set up the environment together and divided the RESTful endpoints, working asynchronously on a couple each. Non-RESTful endpoints were tackled in group coding sessions. Finally, we resolved errors and ensured all tests passed as a team.
- Front-End: We set up the front-end together before splitting tasks for styling and refactoring JavaScript.
- Improvements Made: We enhanced error handling by ensuring the API returned clear messages.  Regarding the FE, we added a Flexbox so the merchants and items were presented more cleanly. We also put extra attention to the making it clear when items on the home page are clickable, by changing the cursor when it hovers over a button, and changing color and font settings when a tab is active.

### Contributors:

- [Kevin Newland](https://github.com/kevin-newland)
- [Kristin Weiland](https://github.com/KMPWeiland)
- [Patrick Shim](https://github.com/pshim17/)
- [Jonathan Atkins](https://github.com/Jonathan-Atkins)

### Learning Goals:
- Use ActiveRecord and SQL to write queries that deal with one-to-many database relationships
- Expose API endpoints to CRUD database resources
- Validate models and handle sad paths for invalid data input
- Test both happy and sad path functionality based on JSON contracts
- Use MVC to organize code effectively, limiting data logic in controllers and serializers
- Track user stories with GitHub Projects
- Improve an existing FE application by:
- Styling the user interface
- Refactoring JavaScript code
- Adding an additional FE feature

### Wins + Challenges:
- Issues with migration tables being down
- Understanding nested resources
- Understanding what to put in Models when utilizing `joins`
- Working through failed tests on Postman as as team
- Improving knowledge of Postman scripts
- Great Team work
- Learning about Student Support(Cydnee Owens)
