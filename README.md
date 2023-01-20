# svelte-package-yarn-workspaces-bug


To reproduce:
- make sure you are running yarn v3
- run `yarn`
- `cd packages/sveltekit-app`
- `yarn build`
- attempt to re-run `yarn` now that the sveltekit `package` output has been created. You will be faced with this error:

<img width="1553" alt="CleanShot 2023-01-20 at 11 24 35@2x" src="https://user-images.githubusercontent.com/1393142/213735246-a068cd5e-d071-48e6-acf7-33dd2b69fd71.png">
