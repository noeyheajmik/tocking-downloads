# tocking application privacy

Updated November 27, 2026. tocking is developed by COCO&TAMY.

## Team-owned hosting

A team administrator installs the team server in that team's own Cloudflare account. Team conversations, files, profiles, membership records, document content, and authentication records are processed by that server. The team administrator controls the hosting account and its access, retention, backups, and deletion settings. Installing the client does not make a workspace public.

## On your device

The client stores local conversation data and preferences and uses the operating system's credential storage for authentication and installation credentials. Passkey registration stores a public-key credential at the team server; the passkey's private key remains managed by your authenticator. Recovery keys exported by an administrator must be kept private.

## Optional connections and shared services

Cloudflare account authorization is used to create and update the team server. Optional Google and Zapier connections process the account authorization and data needed for the actions you choose. The public connection relay handles the corresponding authorization exchanges. Optional notification delivery uses the relevant operating-system push services. Provider permissions, availability, and policies apply to these services.

Do not include private conversations, files, account tokens, or recovery keys in public support issues.

## Website and waitlist

The public tock.ing website uses Google Tag Manager. Waitlist email verification and launch updates have their own notice and email management links. The application and self-hosted conversations are separate from the public landing-page analytics configuration.

## Your requests

Use your workspace's account controls or contact its administrator directly to request access, correction, or removal of team-held data. Closing or deleting an app on a device does not delete the team's Cloudflare server or backups. For general application questions, use the support link at https://github.com/noeyheajmik/tocking-downloads/issues and share only a non-sensitive description.

This notice describes the application architecture. A team's administrator may provide additional information about their own use of the service and the providers they enable.
