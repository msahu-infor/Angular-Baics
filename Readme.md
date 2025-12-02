# Angular Notes

## Section 2: Angular Essentials

Agenda:

- Components
- Templates
- Services & More

Jargons - Markup (HTML)

### Important Notes

- Classes are a standard JavaScript feature (when using modern JavaScript) - it's NOT a TypeScript specific construct.

- Component decorator is a TS feature that adds extra metadata to the class.

- In older versions of Angular, "styleUrl" doesn't exist - use "styleUrls" instead!

- Angular CLI is a command-line interface tool that helps to automate development tasks in Angular projects.

### CLI Commands

- `ng new <project-name>`: Creates a new Angular project.
- `ng serve`: Serves the application locally.
- `ng generate component <component-name>`: Generates a new component.
- `ng generate service <service-name>`: Generates a new service.
- `ng build`: Builds the application for production.
- `ng test`: Runs unit tests for the application.
- `ng lint`: Lints the application code.
- `ng e2e`: Runs end-to-end tests for the application.
- `ng add <package-name>`: Adds a new package to the project.
- `ng update`: Updates the Angular CLI and Angular core packages.
- `ng doc <keyword>`: Opens the official Angular documentation for the specified keyword.
- `ng version`: Displays the current Angular CLI version and Angular packages in the project.

### Property Binding & Outputting Computed Values

- "Property Binding" - a key Angular feature that allows you to bind element properties to dynamic values.

- For example, <img [src]="someSrc"> binds the src property of the underlying HTMLImageElement DOM object to the value stored in someSrc.

### Introduction to Signals

- Signals are a new reactivity primitive in Angular that allow you to manage and react to state changes in the application more effectively.

- Signals can be created using the `signal` function, which initializes a signal with a given value.