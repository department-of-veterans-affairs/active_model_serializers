# ActiveModelSerializers

## About

The repo is a fork of [active_model_serializers 0.10.4](https://github.com/rails-api/active_model_serializers/tree/v0.10.4) for use with [vets-api](https://github.com/department-of-veterans-affairs/vets-api).  `active_model_serializers` after 0.10.4 changes the way `nil` ids are handled by removing the key instead of returning "null", but 0.10.4 is marked as incompatible with Rails 6.  The code here has been modified to remove the Rails restriction and use `module_parent` instead of the now deprecated `parent`.
