<a href="https://fpulse.app?utm_source=github&utm_medium=org">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img alt="F-Pulse App: hear what your users really think" src="assets/banner-light.svg" width="100%">
  </picture>
</a>

<p align="center">
<a href="https://fpulse.app?utm_source=github&utm_medium=org"><img src="https://img.shields.io/badge/Website-fpulse.app-16a34a?style=for-the-badge" alt="Website fpulse.app"></a> <a href="https://fpulse.app/docs?utm_source=github&utm_medium=org"><img src="https://img.shields.io/badge/Docs-REST%20API-0f766e?style=for-the-badge" alt="Docs REST API"></a> <a href="https://fpulse.app/pricing?utm_source=github&utm_medium=org"><img src="https://img.shields.io/badge/Free%20plan-1%2C000%20feedbacks/mo-15803d?style=for-the-badge" alt="Free plan 1,000 feedbacks/mo"></a> <a href="https://fpulse.app/wordpress-plugin"><img src="https://img.shields.io/badge/WordPress-plugin-21759b?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress plugin"></a> <a href="https://x.com/fpulseapp"><img src="https://img.shields.io/badge/Follow-%40fpulseapp-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow @fpulseapp"></a>
</p>

## What F-Pulse App does

Most users leave without telling you why. F-Pulse App puts a small feedback button in your website or app,
collects a rating and a comment in two clicks, and shows you the trend. Its AI reads every comment and tells you
what to fix first, so you spend your time on what actually matters to your users.

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>One line to install</h3>
      Paste one <code>&lt;script&gt;</code> tag, or use the WordPress plugin. Colors, texts and rating type are set in the dashboard.
    </td>
    <td width="33%" valign="top">
      <h3>Any rating you like</h3>
      Thumbs, emoji, 1-5 stars or NPS, with an optional comment and email. Light, dark or automatic theme.
    </td>
    <td width="33%" valign="top">
      <h3>AI that reads it all</h3>
      Summaries of what users say and concrete suggestions, ranked by what to fix first.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h3>Websites and apps</h3>
      The same dashboard for your site, iOS, Android, Flutter and desktop apps through SDKs and a REST API.
    </td>
    <td width="33%" valign="top">
      <h3>Alerts where you work</h3>
      Email alerts and a weekly summary on every plan, plus Slack, ClickUp and signed webhooks.
    </td>
    <td width="33%" valign="top">
      <h3>Dev and production apart</h3>
      Test feedback stays in its own environment, so your real numbers stay clean.
    </td>
  </tr>
</table>

## How it works

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/how-it-works-dark.svg">
  <img alt="Your users rate and comment, the widget or SDK sends it to F-Pulse App, which shows trends and AI suggestions and alerts your team" src="assets/how-it-works-light.svg" width="100%">
</picture>

## Add it in under a minute

**On a website**: copy your snippet from the Widget page of the [dashboard](https://fpulse.app/dashboard/widget?utm_source=github&utm_medium=org) and paste it before `</body>`:

```html
<script src="https://fpulse.app/w/YOUR_WIDGET_ID.js" async></script>
```

**From an app or server**: send feedback with your project API key:

```sh
curl -X POST https://api.fpulse.app/v1/feedback \
  -H "Content-Type: application/json" \
  -H "X-API-Key: fp_your_api_key" \
  -d '{"sentiment": "positive", "comment": "Love the new update", "app_version": "2.1.0", "app_type": "ios"}'
```

Examples for 13 languages, React, Next.js, Vue and webhooks are in [**fpulse-examples**](https://github.com/Fpulse-App/fpulse-examples).

## Works with

**Websites:** <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=white" alt="React"> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"> <img src="https://img.shields.io/badge/Vue-35495E?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue"> <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress"> <img src="https://img.shields.io/badge/Shopify-5E8E3E?style=flat-square&logo=shopify&logoColor=white" alt="Shopify"> <img src="https://img.shields.io/badge/Webflow-146EF5?style=flat-square&logo=webflow&logoColor=white" alt="Webflow"> <img src="https://img.shields.io/badge/Wix-0C6EFC?style=flat-square&logo=wix&logoColor=white" alt="Wix"> <img src="https://img.shields.io/badge/Squarespace-000000?style=flat-square&logo=squarespace&logoColor=white" alt="Squarespace"> <img src="https://img.shields.io/badge/Google%20Tag%20Manager-246FDB?style=flat-square&logo=googletagmanager&logoColor=white" alt="Google Tag Manager">

**Apps and servers:** <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift"> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin"> <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"> <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP"> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"> <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust"> <img src="https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white" alt="Ruby"> <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET"> <img src="https://img.shields.io/badge/Java-437291?style=flat-square&logo=openjdk&logoColor=white" alt="Java"> <img src="https://img.shields.io/badge/Elixir-4B275F?style=flat-square&logo=elixir&logoColor=white" alt="Elixir">

**Your tools:** <img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square" alt="Slack"> <img src="https://img.shields.io/badge/ClickUp-7B68EE?style=flat-square&logo=clickup&logoColor=white" alt="ClickUp"> <img src="https://img.shields.io/badge/Webhooks-374151?style=flat-square" alt="Webhooks"> <img src="https://img.shields.io/badge/Zapier-FF4F00?style=flat-square&logo=zapier&logoColor=white" alt="Zapier"> <img src="https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white" alt="Make"> <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n">

## Repositories

| Repository | What's inside |
|------------|---------------|
| [**fpulse-examples**](https://github.com/Fpulse-App/fpulse-examples) | Widget setups (HTML, React, Next.js, Vue, WordPress plugin), REST API clients in 13 languages, webhook receivers with signature checks |
| [**feedbackPulse**](https://github.com/ztuskes/feedbackPulse) | iOS and macOS SDK (Swift Package Manager) with a ready-made SwiftUI feedback sheet |

## Plans

| | Free | Pro | Enterprise |
|---|:---:|:---:|:---:|
| Price | $0 | $19 / month | $39 / month |
| Feedbacks per month | 1,000 | 50,000 | Unlimited |
| Projects | 1 | 5 | Unlimited |
| Team members | 1 | 5 | 25 |
| History | 7 days | 90 days | 365 days |
| AI analysis, Slack, ClickUp, webhooks | | ✓ | ✓ |
| Zapier, Make, n8n, SSO | | | ✓ |

Yearly billing: $199 for Pro, $399 for Enterprise. [Start free](https://fpulse.app/auth/register?utm_source=github&utm_medium=org), no credit card needed.

---

<p align="center">
  <a href="https://fpulse.app?utm_source=github&utm_medium=org">Website</a> ·
  <a href="https://fpulse.app/docs?utm_source=github&utm_medium=org">Documentation</a> ·
  <a href="https://fpulse.app/demo?utm_source=github&utm_medium=org">Live demo</a> ·
  <a href="https://fpulse.app/blog?utm_source=github&utm_medium=org">Blog</a> ·
  <a href="https://fpulse.app/contact?utm_source=github&utm_medium=org">Contact</a>
</p>
