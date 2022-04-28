# turbo-test-issue
A reproduction of https://github.com/vercel/turborepo/issues/1140

Simply install and run the root `test` script:

    npm install && npm test

Observe how neither "test" nor "tests" end up in the "Packages in Scope".
