# Lighthouse Audit Results

## Overview

A Lighthouse audit was performed on the Flipkart website to review its performance, accessibility, best practices, SEO, and user experience.

## Lighthouse Scores

| Category | Score |
|---|---:|
| Performance | 62/100 |
| Accessibility | 81/100 |
| Best Practices | 96/100 |
| SEO | 92/100 |
| Agentic Browsing | 1/2 |

## Performance Metrics

| Metric | Result |
|---|---:|
| First Contentful Paint (FCP) | 1.8 s |
| Largest Contentful Paint (LCP) | 2.7 s |
| Total Blocking Time (TBT) | 2,130 ms |
| Cumulative Layout Shift (CLS) | 0.002 |
| Speed Index | 6.0 s |
| Interaction to Next Paint (INP) | 451 ms |
| Time to First Byte (TTFB) | 1.4 s |

The Core Web Vitals assessment was marked as failed.

## Main Performance Findings

- Main-thread work was about 8.9 seconds.
- JavaScript execution was about 5.2 seconds.
- Around 3,671 KiB of unused JavaScript was identified.
- Around 40 KiB of unused CSS was identified.
- Network payload was about 2,957 KiB.
- Potential image delivery savings were about 243 KiB.
- 20 long main-thread tasks were identified.
- 11 animated elements were identified.

## Accessibility Findings

The audit identified the following areas for improvement:

1. The viewport configuration restricts user scaling.
2. A main landmark was not identified.
3. Some identical links serve the same purpose.
4. Some elements have insufficient color contrast.
5. Some links do not have a discernible name.
6. Additional accessibility checks require manual review.

## Best Practices

Browser errors were reported in the console during the audit.

## SEO Findings

Some links were identified as not being crawlable.

## Agentic Browsing

The accessibility tree was not well formed for agentic browsing.

## Recommended Improvements

- Reduce unnecessary JavaScript and CSS.
- Improve page loading and main-thread performance.
- Optimize images and other network resources.
- Improve color contrast.
- Provide clear names for links and interactive elements.
- Review the page landmark and heading structure.
- Check keyboard navigation manually.
- Resolve browser console errors.
- Review links for better crawlability.

## Conclusion

The Lighthouse audit provides a clear view of the current website quality and highlights areas that can be improved. Performance, accessibility, SEO, and keyboard usability should be reviewed together to create a more efficient and accessible user experience.
