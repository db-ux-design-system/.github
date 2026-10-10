# Accessibility

We aim to provide an accessible Design System and support the teams using it in building accessible applications. This involves both the components themselves and guidance on how to use them within an application.

## How the Design System supports you

DB UX Design System uses semantic HTML and ARIA roles, states and properties where appropriate. We quality-check our work in partnership with the [Team Digital Accessibility](https://db.de/8pei5n).

Our [component documentation](https://design-system.deutschebahn.com/) provides a starting point for implementation. Please consider the guidance for the individual component, especially when adapting examples or composing components into more complex interactions.

## Accessibility in your application

The accessibility of an application also depends on its content, configuration and how components are combined. For example, a form control still needs a meaningful label, and a dialog needs to fit the focus behaviour of the surrounding application.

Please test the actual implementation in your application, including keyboard interaction and use with assistive technologies. Using the Design System alone does not establish accessibility conformance for the complete application.

## Report an accessibility issue

If you encounter a barrier in our components or documentation, please [open an issue](./issues/new). Include the component and package version, steps to reproduce the problem, and the expected behaviour. Where relevant, also include the browser and assistive technology used.

You can check the [existing issues](./issues) first to see whether the problem has already been reported.

Feedback from applications using the Design System helps us identify barriers and improve both the components and their documentation.
