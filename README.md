# Macaron Canary

This is an informational and archival project dedicated to warrant canaries, National Security Letters, and related areas.

## Current Version: 0.0.1

[CHANGELOG](https://github.com/MacaronCanary/MacaronCanary/blob/master/CHANGELOG.md) for more details.

## Development

The purpose of this repository is to serve as a way to easily view the entirety of the project and denote official versions. This repository is split in multiple branches and repositories with the work flow as such:

```
# Features
# Create feature specific branches using the following branch naming convention in their correct development repositories:
feature/{name}-{optional version/person/etc.}            # New features
fix/{feature}-{issue}-{optional version/person/etc.}     # Fixing an existing feature
update/{feature}-{fix}-{optional version/person/etc.}    # Updating an existing feature

# Development
# Feature branches get pushed into their respective branches in MacaronCanary/MacaronCanary from the development repositories.
frontend      # MacaronCanary/www
backend       # MacaronCanary/www-server
macarons      # MacaronCanary/macarons

# Staging to Production
staging       # Development branches staged here for master
master        # All branches begin here
production    # Deployed and live production version
```

## Contributing

There are many ways to contribute whether asking questions; reporting bugs; suggestions, feedback, and discussions on features; submitting a PR, and more. The best way to begin is to create an [issue](https://github.com/MacaronCanary/MacaronCanary/issues). Lets talk!

## Security Policy

If you have discovered a vulnerability you may voluntarily report it to security@macaroncanary.com. Please visit the main [Security Policy](https://github.com/MacaronCanary/MacaronCanary/security/policy) page for further details and information.

## License

[GNU Affero General Public License v3.0](https://github.com/MacaronCanary/MacaronCanary/blob/master/LICENSE)