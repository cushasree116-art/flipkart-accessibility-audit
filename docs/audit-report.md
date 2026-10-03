# 🔎 Flipkart Accessibility Audit Report

## 1. Executive Summary

A usability and accessibility audit was carried out on the Flipkart website using WAVE, Lighthouse, and keyboard-navigation checks.

The audit identified opportunities to improve accessibility, page structure, link clarity, color contrast, and loading performance.

The goal of this report is to present the findings clearly and provide practical recommendations for improvement.

## 2. Lighthouse Results

| Metric | Result |
|---|---:|
| Performance | 62/100 |
| Accessibility | 81/100 |
| Best Practices | 96/100 |
| SEO | 92/100 |
| First Contentful Paint | 1.8 s |
| Largest Contentful Paint | 2.7 s |
| Total Blocking Time | 2,130 ms |
| Cumulative Layout Shift | 0.002 |
| Speed Index | 6.0 s |

The Lighthouse results showed performance and accessibility areas that can be improved.

## 3. Accessibility Findings

### 🖼️ Issue 1: Alternative Text

**WCAG:** 1.1.1 Non-text Content  
**Priority:** High

Some images or visual elements need meaningful alternative text.

**Recommendation:**
- Add useful alternative text to informative images.
- Use empty `alt=""` for decorative images.
- Avoid unnecessary or repeated alternative text.

### 🎨 Issue 2: Color Contrast

**WCAG:** 1.4.3 Contrast (Minimum)  
**Priority:** High

Some content has insufficient color contrast.

**Recommendation:**
- Improve foreground and background contrast.
- Check text against WCAG contrast requirements.
- Re-test after making changes.

### 🔗 Issue 3: Link Names

**WCAG:** 2.4.4 Link Purpose  
**Priority:** High

Some links do not have a clear discernible name.

**Recommendation:**
- Use descriptive link text.
- Provide accessible names for icon-only links.
- Make the purpose of each link clear.

### 📝 Issue 4: Heading Structure

**WCAG:** 1.3.1 Info and Relationships  
**Priority:** Medium

The heading organization needs review for a logical structure.

**Recommendation:**
- Use a clear heading hierarchy.
- Keep heading levels in a logical order.
- Do not use headings only for visual styling.

### 🧭 Issue 5: Main Landmark

**WCAG:** 1.3.1 Info and Relationships  
**Priority:** Medium

Lighthouse reported that the document does not have a main landmark.

**Recommendation:**
- Use a semantic `<main>` element for the primary page content.
- Keep the main content clearly separated from navigation and other page regions.

## 4. Performance Priorities

The Lighthouse audit highlighted areas including:

- High Total Blocking Time
- Long main-thread tasks
- JavaScript execution
- Unused JavaScript
- Unused CSS
- Large network payloads
- Image-delivery opportunities

**Recommended actions:**

- Reduce unnecessary JavaScript.
- Remove or reduce unused CSS and JavaScript.
- Optimize images.
- Reduce long-running main-thread tasks.
- Improve page loading and interactivity.

## 5. Keyboard Navigation

The keyboard test should verify:

1. Interactive elements can be reached using the `Tab` key.
2. The current focus is clearly visible.
3. `Shift + Tab` moves focus backwards correctly.
4. Links and buttons can be activated using the keyboard.
5. Focus moves in a logical order.

Evidence screenshots should be stored with the project.

## 6. Recommended Priorities

| Priority | Area | Recommended Action |
|---|---|---|
| High | Accessibility | Improve contrast, accessible names, and alternative text |
| High | Performance | Reduce JavaScript and main-thread work |
| Medium | Page Structure | Improve headings and semantic landmarks |
| Medium | Usability | Complete keyboard-navigation testing |
| Low | Documentation | Keep audit evidence and findings updated |

## 7. Conclusion

The audit provides a practical list of areas for improving accessibility, performance, and usability.

After improvements are implemented, WAVE and Lighthouse should be run again to verify the changes and measure progress.
