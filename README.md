# sentry-5-integrations-typescript-angular-bug
https://github.com/getsentry/sentry-javascript/issues/1985
## Steps
1. Run `npm install` or `yarn`
2. Run `npm run typecheck` or `yarn typecheck`
```
node_modules/@sentry/integrations/dist/angular.d.ts:1:23 - error TS2688: Cannot find type definition file for 'angular'.

1 /// <reference types="angular" />
                        ~~~~~~~

node_modules/@sentry/integrations/dist/angular.d.ts:33:19 - error TS2503: Cannot find namespace 'ng'.

33         angular?: ng.IAngularStatic;
                     ~~


Found 2 errors.
```
