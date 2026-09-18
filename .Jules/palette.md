## 2025-02-18 - Icon-Only Buttons and Dynamic Mobile Menus
**Learning:** Icon-only navigation buttons and social links in Blade layout templates often lack explicit ARIA labels and focus-visible indicators, making them unannounced to screen readers and difficult to navigate via keyboard. Dynamic menus also need `aria-expanded` state tracking.
**Action:** Always inspect main layout views for icon-only buttons/links, add `aria-label`, mark internal icon tags with `aria-hidden="true"`, include `focus-visible:ring-2` styles, and toggle `aria-expanded` via JavaScript when menus open/close.
