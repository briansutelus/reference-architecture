# Accessiblity Testing

## Why

Ensuring all your users, including those with disabilities, are able to effectively use your application with a good user experience is a critical aspect to any Testing practice. Using tools such as Wave and aXe will allow you to quickly evaulate your feature's accessibility quality and provide feedback on how your team can improve on the feature to make it more accesible.

## What

Configure and run tests automatically in your pipeline

## How

Use [axe](https://www.deque.com/axe/) to accessiblity test after the application is deployed to staging.

## When

Writing accessiblity tests: Up on story completion, make sure to include the assertion, also make sure to pull the latest starter-kit change regarding accessiblity checklist

Running accessiblity tests: As part of the delivery pipeline

## Who
@delivery @dev

## Standards

### 4.14.1 Accessibility Testing Tools
- [WAVE](https://wave.webaim.org/) - WAVE is a web accessibility evaluation tool, which can identify many Web Content Accessibility Guideline issues from a browser extension.

- [axe](https://www.deque.com/axe/) - axe is another popular web accessibility browser extension that can help identify any accessibility issues from within the browser.

  - [axe-core-npm](https://github.com/dequelabs/axe-core-npm) - an npm module that can be integrated into any CI/CD pipeline to automate accessibilty checks and provide a score based accessibility compliance and issues.