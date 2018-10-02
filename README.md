# Hacktoberfest 2018 Code Challenges

The point of this repository is to allow anyone to start contributing on a
public repository.

## Installation

```bash
# Clone repo
git clone git@github.com:rgehan/hacktoberfest-2k18-katas.git

# Install the dependencies
yarn
```

## How to participate

1. Find an issue that is **not assigned** yet
2. Implement it so that it passes all the tests (check with `yarn test src/theFunction.test.js`)
3. Add a test case for a new function. You can use `yarn generate` to create the two new files.
4. Create your **Pull Request**
5. Create an issue for your new feature

## Some rules & directions

- No libraries of any kind, just plain old vanilla js :)
- If you got assigned an issue and don't have time to do it, please say it so we can release it for someone else.
- Make sure your implementation passes the previous tests before opening a Pull Request.

## Files

When using `yarn generate`, two files are created:

**theFunction.js**:

```js
export const ${name} = () => {
  // TO IMPLEMENT IN ANOTHER PR
};
```

**theFunction.test.js**:

```js
import { ${name} } from './${name}';

describe('${name}', () => {
  it('does something', () => {
    expect(true).toBeTruthy(); // TODO Your test instead
  });

  it('does something else', () => {
    expect(true).toBeTruthy(); // TODO Your test instead
  });
})
```

You only need to update the test file, the actual implementation will be done
by someone else!
