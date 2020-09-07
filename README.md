# securra-sentry-wrapper

This module provides a convenient configuration of the sentry [`sentry`](https://github.com/getsentry/sentry-javascript)
Sentry client for usage in the securra multiple projects and
related modules.

It currently provides the following features:
* It exports the `sentry` API as is, no wrapper, no modifications.
* Convenience function to init sentry witch set some configuration from config which each project will have.
