## Usage

```bash
npm i 
npm run codegen
```

- Select something, for example, the search input and the 'GET STARTED' element.
- You will see the generated code is not using `getByTestId(testId)`
- Or you can change the `testIdAttribute` and try other websites. It will not generate code with `getByTestId(testId)` either. For example, `data-ph-id` with https://jobs.microfocus.com/global/en/