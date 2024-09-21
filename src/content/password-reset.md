---
layout: transactional
title: "Password Reset"
---

# {{ page.title }} { .text-lg }

---

Hello @{{ user.firstName }},

@{{ verification.code }}{ .text-2xl .font-semibold } 

is your code for resetting your password.

\
Yours Sincerely,\
The Easworks Team

<push name="post-main-content">
  <!-- <tr><td class="p-1"></td></tr> -->
  <tr><td class="py-2 px-4 text-center text-slate-500 text-sm">
    If you are not the one who initiated this action, you can safely ignore this email.
  </td></tr>

</push>

