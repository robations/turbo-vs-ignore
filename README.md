# Set up

```
pnpm i
pnpm turbo run test
pnpm turbo run test

# ^ hashes will change between builds
```

Uncomment the workaround in [the .gitignore](packages/foo/.gitignore).

```
pnpm turbo run test
pnpm turbo run test
```

You should now see the hash is stable between test runs.