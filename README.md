# Toolkit Comparison

In this project, we aim to compare as many UI toolkits/frameworks we can get our
hands on to find out how they stack up in the following categories:

- Accessibility
- Resource usage
- Start-up time
- Cross platform support
- Developer experience
- Looks

## Ground Rules

Any programming language is allowed, but if the UI toolkit has a language it is
native to, use that. (E.g. Dart for Flutter, Swift for SwiftUI)
Don't use wrappers or adapters unless these are somehow unavoidable or extremely
common practice for a specific toolkit.

Web-UI wrappers (Electron, Wails, etc.) should share a common vanilla JS code as
far as possible. We are not measuring the performance of different JS frameworks
here.

Projects should be as stock as possible. No intricately crafted compiler
configuration, no custom extensions in other languages, no extra dependencies
unless it is common practice for the toolkit.

Each toolkit gets its own GitHub repo within the
[ui-comparison](https://github.com/ui-comparison) org. Results are captured in
each project, then aggregated
[here](https://github.com/ui-comparison/Toolkit-Comparison-Main). These repos
will be licensed as CC0 if possible, or the most permissive license possible
otherwise.

All measurements will be made on each supported system separately. So we will
note if some features only work on specific platforms.

## Accessibility

We will check how well the application can be used with assistive technologies
or different input methods.

Currently we will check:

- Keyboard navigation
- Screen reader support
- Touch compatibility
- Gamepad compatibility

## Resource Usage / Start-up Time

For each project, these measurements will be taken:

- Size of executable
- Ram usage
- Start-up time

Each measurement for each platform will be made on the same test machine.

## Developer Experience

These are of course highly subjective, so we can't exactly measure them.
Instead, you can judge the source code for each implementation to see if you'd
like to work with that framework.

## Looks

Similarly to the developer experience, this is subjective. Each project will
provide screenshots for each supported platform, so you can judge if you like
the look.

We will note for each toolkit if theming is supported, how extensive it is, and
if it can automatically adjust to fit the system theme.
