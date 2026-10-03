# Flipkart Accessibility & Lighthouse Audit

## Project Overview

This project presents an accessibility and Lighthouse audit of the Flipkart website.

The audit focuses on accessibility, performance, best practices, SEO, and usability. The findings are documented in a simple and organized project structure.

## Website Audited

**Website:** Flipkart

**URL:** https://www.flipkart.com/

## Tools Used

- Lighthouse
- WAVE Accessibility Evaluation Tool
- Keyboard Accessibility Review
- GitHub

## Lighthouse Results

| Category | Score |
|---|---:|
| Performance | 62/100 |
| Accessibility | 81/100 |
| Best Practices | 96/100 |
| SEO | 92/100 |
| Agentic Browsing | 1/2 |

## Key Performance Results

- First Contentful Paint (FCP): 1.8 s
- Largest Contentful Paint (LCP): 2.7 s
- Total Blocking Time (TBT): 2,130 ms
- Cumulative Layout Shift (CLS): 0.002
- Speed Index: 6.0 s
- Interaction to Next Paint (INP): 451 ms
- Time to First Byte (TTFB): 1.4 s

## Main Accessibility Findings

The audit identified several areas that can be improved:

1. Missing or incorrect alternative text
2. Low color contrast
3. Heading structure issues
4. Unhelpful alternative text
5. Weak page structure or missing main heading

## Other Audit Findings

- The viewport configuration restricts user scaling.
- A main landmark was not identified.
- Some identical links serve the same purpose.
- Some links do not have a discernible name.
- Browser errors were reported in the console.
- Some links were identified as not being crawlable.
- The accessibility tree was not well formed for agentic browsing.

## Recommended Improvements

- Add meaningful alternative text to important images.
- Improve color contrast.
- Maintain a clear heading hierarchy.
- Provide useful names and descriptions for images and links.
- Use appropriate semantic landmarks.
- Improve keyboard accessibility.
- Reduce unnecessary JavaScript and CSS.
- Optimize images and other page resources.
- Review browser console errors.
- Improve link crawlability.

## Keyboard Accessibility

A keyboard accessibility check was included as part of the project.

The test method includes:

- Using the Tab key to move between interactive elements.
- Checking whether the focused element has a visible focus indicator.
- Using Enter or Space to activate links and buttons.
- Checking whether the expected action occurs.

The keyboard test should be performed using a physical keyboard on the website.

## Evidence

The project includes Flipkart screenshots collected during the audit.

Evidence files include:

- `flipkart-home.png`
- `flipkart-shopping.png`

These screenshots document the website interface and support the audit documentation. They do not by themselves prove keyboard focus or keyboard activation behavior.

## Project Structure

flipkart-accessibility-audit/
├── docs/
│   ├── accessibility-issues.md
│   ├── architecture.md
│   ├── audit-report.md
│   ├── keyboard-test.md
│   ├── lighthouse-results.md
│   ├── flipkart-home.png
│   └── flipkart-shopping.png
├── README.md
├── README.pdf
└── architecture.pdf

## Documentation

### Audit Report

Contains the overall accessibility and Lighthouse audit findings.

### Accessibility Issues

Contains five major accessibility issues and recommended improvements.

### Lighthouse Results

Contains Lighthouse scores, performance metrics, and major findings.

### Keyboard Test

Contains the keyboard accessibility testing method, expected results, and evidence information.

### Architecture

Describes the project structure and organization.

### Evidence

Contains screenshots collected during the audit.

## Project Goal

The goal of this project is to identify accessibility, performance, usability, and SEO-related issues and document practical improvements.

## Conclusion

This project provides a structured review of the Flipkart website using accessibility and Lighthouse auditing methods.

The documented findings can be used as a reference for improving accessibility, performance, usability, and overall website quality.
