# notest

![notest](./notest.jpeg)

The best way to write deterministic and scalable test suites. Test nothing; find bugs nowhere.

~~I am a sibling of [nocode](https://github.com/kelseyhightower/nocode).~~

## Getting Started

Start by not writing any tests.

```

```

This is just an example empty test, but imagine it asserting anything you want. Adding new tests is easy too:

```

```

The possibilities are endless.

### Running the Tests Locally

Now that you have not test anything it's time to run your tests:

```

```

Yep. That's it. You should see the following output:

```

```

### Running the Tests in CI

While you still have not test anything it's time to make the tests run in CI as well. By adding the following lines anywhere in your CI config, you can test absolutely nothing.

```

```

It's that simple. And you know the tests will add zero overhead to your CI runtime, and they will be completely deterministic across all platforms.

### How to Deal with LOC-oriented Performance Rating

Your boss might be unhappy about you writing zero lines of tests. Fortunately, you can do:

```
exit 0
```

## Contributing

You don't.
