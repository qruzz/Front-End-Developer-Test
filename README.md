# Front-End Developer Test

This test is created to test your coding style and general problem solving skills. As the company is using the [React Framework](https://reactjs.org) we are asking you to create the markup in JSX, and style it using Pure CSS (no pre-processors) without the usage of pre-built grids or libraries like Foundation or Bootstrap. Also, no jQuery usage - only vanilla JavaScript.

This is a "take-home" test, which means that there is no real time limit for completion. It is better to complete it well, then rushing it, although one should strive to complete it within 3 days.

## Project Brief

In the git repository, a resources folder has been created with a Sketch file, and all static exports needed to complete the test.

Take a look at the files, and convert the designs to JSX/CSS. Some level of responsiveness is expected, although not all use cases needs to be implemented - mobile and larger laptop screens will suffice.

I have created a React Project in the git repository, so all you have to do is follow the initial requirements to get started.

P.S. If you want us to follow along on your progress, commit regularly to git.

## Requirements

1. Fork the git repository and pull it onto your development machine.
2. Initialise the projects by running `yarn` or `npm install` (depending on what package manager you prefer).
3. Use JSX and CSS to build the design.
4. Create some simple hover effects for the image thumbnails.
5. Make the site responsive using your best judgement.
6. Make the page the smallest possible size - ensure that images are properly optimised, resources minified, etc.

## Design

The design file is accessible in the resources folder in the git repository, but also available on InVision for the coding specs (colours, fonts, pixel sizing and so on).
You do not have to stick 100% to the sizing provided, but it is there as a guideline.
You can access the InVision project [here](https://projects.invisionapp.com/project/14733900)
The following images are used in the design:
- [Roadtrip Image](https://unsplash.com/photos/9Eps5tTicWw)
- [Balloon Image](https://unsplash.com/photos/zdIU7W5G5Ts)
- [Surfing Image](https://unsplash.com/photos/_CFv3bntQlQ)
- [Coffee Image](https://unsplash.com/photos/WdG6II80oBE)
- [Desert Image](https://unsplash.com/photos/JgZqdpWp0M4)
- [Japan Image](https://unsplash.com/photos/MsMISAIe8Qw)

## Supported Browsers

Ensure that the elements work and display correctly in the following browsers:
- Firefox (latest version)
- Google Chrome (latest version)
- Opera (latest version)
- Safari (latest version)

## Coding Standards

When working on the project, try to use a consistent coding style. At the company, we are using [ESLint](https://eslint.org) to ensure a consistent code quality. I have included our internal ESLint file in the repository.

To install the necessary dependencies for ESLint to work, I will provide the needed dev dependencies for the package.json below:

```json
{
  "devDependencies": {
    "eslint": "^4.14.0",
    "eslint-config-airbnb": "^16.1.0",
    "eslint-plugin-import": "^2.8.0",
    "eslint-plugin-jsx-a11y": "^6.0.3",
    "eslint-plugin-react": "^7.5.1",
    "eslint-plugin-react-native": "^3.2.0"
  }
}
```

## Quality Assurance

What do you need to get a high QA score?
If you can answer yes to most of the below questions, you are good to go.

### General
- Do you meet all requirements set above?
- Can the project be built using `npm run build` or `yarn build`?
- Is the page working without any JS errors?
- Is your code commented and documented?

### Browser Check
- Does the page display and work correctly in listed *supported browsers*?

### Coding Standards
- Is the page using a consistent JSX coding style?
- Is the page using a consistent CSS coding style?
- is the page using a consistent JS coding style?

### Optimisation
- Are all image files sufficiently compressed?

### Accessibility
- Are proper ALT attributes for images provided?

## Closing Remarks

Feel free to be as creative with the solution as you wish. Nothing more than what is presented in this file is expected, although if you feel like adding anything to display your skills, feel free to do so.