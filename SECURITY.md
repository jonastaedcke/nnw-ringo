# Security policy

This policy covers the Ringo theme for NetNewsWire and its website,
<https://ringo-the.me/>.

## Supported versions

Security fixes go into the latest release of Ringo only. The website is always
the version that is online.

## Reporting a vulnerability

Please do not open a public issue. Send your report to
**<security@ringo-the.me>** instead. You will get an answer within a few hours.
Please keep the details private until a fix is out.

Please include:

- the Ringo and NetNewsWire versions, and your device and its OS version, or for
  the website, the affected page and your browser
- the steps to reproduce it, or the feed or article that triggers it
- the impact you observed

## What counts as a vulnerability

Ringo's template and scripts run in NetNewsWire's article view on HTML from
feeds that nobody controls. These reports are the most important:

- scripts that run when they should not, such as a feed's markup that Ringo's
  scripts turn into executable code
- content that escapes the article, such as a feed's markup that covers or
  imitates NetNewsWire's or Ringo's own interface
- requests or navigation that Ringo starts without the reader asking, or that
  leak data about the reader
- a theme bundle or update that does not come from this project
- on the website, anything that gets past its content security policy, or that
  leaks data about its visitors beyond what its privacy notice names

Problems that also occur with NetNewsWire's built-in themes belong to
NetNewsWire: please report them to the
[NetNewsWire project](https://github.com/Ranchero-Software/NetNewsWire).
