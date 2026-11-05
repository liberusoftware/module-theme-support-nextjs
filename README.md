# Theme Support · Next.js · React

Independent presentation module skeleton for **Theme Support**. Intended boundary: independent react application with explicit next.js server/client boundaries.

**Status: skeleton.** This repository supplies package/build structure and an explicit extension entry. It is not a completed feature, production API integration or registry publication. Existing implementations and package identities remain authoritative.

- Capability/source key: `liberusoftware/theme-support`.
- Presentation scope: [Theme Support](https://github.com/liberusoftware/documentation/blob/main/projects/boilerplate/nextjs/theme-support.md).
- Canonical ownership record: [source/plan group](https://github.com/liberusoftware/documentation/blob/main/projects/boilerplate/nextjs/theme-support.md).
- Registry identity: `@liberusoftware/module-theme-support-nextjs`.
- Foundation: [module-boilerplate-nextjs](https://github.com/liberusoftware/module-boilerplate-nextjs) at `f36c3c383b38a8ebedb343dffa24cf64bec1817b`.

## Develop and verify

```bash
npm ci
npm run typecheck
npm run build
npm pack --dry-run
```

The public npm export currently provides `moduleDefinition`, explicit registration metadata. No UI screens or API calls are implemented. Add capability UI and injected contract mapping through deliberate exports.

Use the committed locks and declared toolchain. Read [AGENTS.md](AGENTS.md) and the [presentation runbook](https://github.com/liberusoftware/documentation/blob/main/guides/presentation/NEXTJS.md). Keep host routing, navigation, session integration and deployment outside reusable capability code. Keep Laravel policy, tenant context, validation, transactions, persistence and state transitions in the canonical owner. Do not infer endpoints or business DTOs from this registration descriptor.

Implement reviewed loading, empty, denied, invalid, stale/conflict, pending and recoverable failure states when adding real workflows. Test meaningful allowed/denied/wrong-tenant behavior against the authoritative API or public action. Reconcile uncertain writes before retrying and clear scoped cached data on logout. For device targets, review lifecycle, secure storage and platform support; a local draft is not a completed server transaction.

## Documented consumer project families

These project skeletons belong to documented consumer scopes. Their presence does not prove integration or feature parity; review compatible core/API contracts before enabling this package.

- [Boilerplate](https://github.com/liberusoftware/project-boilerplate-next-react): Shared application foundation and module composition.
- [Accounting ERP](https://github.com/liberusoftware/project-accounting-erp-next-react): Ledgers, tax, reporting and finance workflows.
- [Automation](https://github.com/liberusoftware/project-automation-next-react): AI gateways, approvals, rules and integrations.
- [Billing](https://github.com/liberusoftware/project-billing-next-react): Subscriptions, pricing, payments and provisioning.
- [Browser Game](https://github.com/liberusoftware/project-browser-game-next-react): Game worlds, players and community workflows.
- [Control Panel](https://github.com/liberusoftware/project-control-panel-next-react): Infrastructure and hosting operations.
- [CRM](https://github.com/liberusoftware/project-crm-next-react): Relationships, sales pipelines and customer service.
- [Genealogy](https://github.com/liberusoftware/project-genealogy-next-react): Family trees, research, evidence and collaboration.
- [Maintenance](https://github.com/liberusoftware/project-maintenance-next-react): Assets, work orders, schedules and field operations.
- [Real Estate](https://github.com/liberusoftware/project-real-estate-next-react): Listings, sales, lettings and agency operations.
- [Social Network](https://github.com/liberusoftware/project-social-network-next-react): Profiles, feeds, communities and moderation.

## Other presentations of this capability

The companion repositories use the same canonical scope and preserve their own presentation lifecycle. Availability is recorded by the repository inventory; a repository link is not evidence of an implemented feature.

- [Laravel · Filament](https://github.com/liberusoftware/module-theme-support-filament).
- [Laravel · Inertia · Vue](https://github.com/liberusoftware/module-theme-support-vue-inertia).
- [Laravel · Inertia · React](https://github.com/liberusoftware/module-theme-support-react-inertia).
- [Nuxt · Vue](https://github.com/liberusoftware/module-theme-support-nuxt).
- [React Native · Expo](https://github.com/liberusoftware/module-theme-support-react-native).
- [Flutter · Mobile](https://github.com/liberusoftware/module-theme-support-flutter).
- [Dart · Desktop](https://github.com/liberusoftware/module-theme-support-dart-desktop).
- [Dart · Mobile](https://github.com/liberusoftware/module-theme-support-dart-mobile).

## Release boundary

Build and inspect a packed artifact in a clean consumer before an authorized registry release. Keep prerelease/skeleton status until implemented behavior and supported runtimes are verified. Repository creation does not publish to Packagist, npm or pub.dev. Native signing and store distribution are separate application responsibilities.
