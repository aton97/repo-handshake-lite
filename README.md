# Repo Handshake Lite

**Free GitHub client-delivery kit for freelance developers.**

Repo Handshake Lite gives you a lightweight operating loop for client work inside GitHub: lock what is in scope, separate extra requests, keep Pull Requests tied to tracked work, and generate a weekly list of what actually shipped.

## The problem

Client delivery gets messy when scope lives in chat, "small extras" are implemented without a decision, and weekly updates depend on memory.

Repo Handshake Lite adds a simple rule:

> **Do not implement out-of-scope work before the matching Change Request is explicitly approved.**

## What's included

- Bug issue form
- In-scope Feature issue form
- Out-of-scope Change Request form
- Pull Request delivery checklist
- CODEOWNERS starter
- Weekly GitHub Action that lists merged PRs
- Kickoff checklist

## 10-minute setup

1. Copy the `.github` folder into the repository where you deliver client work.
2. Edit `.github/CODEOWNERS` and replace `@aton97` with your GitHub username or team.
3. Commit the files to your default branch.
4. Open **Actions → Repo Handshake weekly delivery summary → Run workflow** once.
5. Create work using the Bug, Feature, or Change Request forms.
6. Link each Pull Request to the tracked work it delivers.
7. Every week, use the generated delivery log as the raw material for your client update.

The workflow also runs every Monday at **14:00 UTC**.

## Delivery loop

`Scope → Issue → Code → Pull Request → Merge → Weekly delivery log`

For out-of-scope work:

`Client request → Change Request → impact/decision → Approved → implementation`

## Lite vs Pro

| Lite — free | Repo Handshake Pro |
| --- | --- |
| GitHub delivery kit | Full GitHub + Notion Client Delivery OS |
| Kickoff checklist | 7 connected Notion databases |
| Change Request gate | Client / engagement dashboards |
| PR checklist | Weekly client-status workflow |
| Weekly merged-PR log | Invoice status, acceptance and access handoff |
| Self-managed | EN/ES operating templates + worked example |

## Repo Handshake Pro pilot

The Pro version adds the client/commercial operating layer in Notion while GitHub remains the source of truth for technical delivery.

Pilot access is being validated with a small group of freelance developers. If you want to test it, open a **Pro pilot interest** issue in this repository.

## Safety

Do not place passwords, tokens, private keys, recovery codes, `.env` files, or other secrets in Issues, Pull Requests, or delivery logs.

## What this is not

Repo Handshake is not a contract, invoicing platform, accounting system, or tax tool. Lite is deliberately small: it helps you make delivery visible and scope changes explicit.
