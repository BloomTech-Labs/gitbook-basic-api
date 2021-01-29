# Example routes of resources

Some examples of routes are provided.

## Simple Non-resource route

The `/` (index) route is a simple `GET` route that is not tied to a resource.

## Full CRUD for a single resource

The `/profile` route is dedicated to a single resource (model).

This route provides CRUD operations on the profile model.
Profile is a replacement for the notion of a User when using an identity
provider (Okta) where Users are owned by the third party service.

## Wrapper Routes

The `/data` routes are wrappers around an internal API (DS resources)

When working on a project that has other services being created Labs wants
you to keep those behind a single authenticated server. This API starter
shows an example of wrapping these services.

Notice that the `/data/predict` route is not merely a copy of the DS
service but creates a path that may be esasier for the FE to consume. Make
sure to work with the owner of the service to understand it's use and if
such a change will work.
