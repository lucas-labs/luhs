<p align="left">
    <img src="./media/logo.svg" height="30"> 
    <span><strong>&nbsplucaslabs home-server<strong></span>
</p>

------------ 

## Dev commands

### serve
* `pnpm serve` - start dev server for both frontend and backend
* `pnpm serve:fe` or `pnpm serve:dashboard` - start dev server for frontend
* `pnpm serve:be` or `pnpm serve:luhs` - start dev server for backend

### build
* `pnpm build` - build both frontend and backend
* `pnpm build:fe` or `pnpm build:dashboard` - build frontend
* `pnpm build:be` or `pnpm build:luhs` - build backend

### format
* `pnpm format:list` - list all files that need to be formatted (files that will be changed if you run `pnpm format`)
* `pnpm format` - format all files

### nx
* `pnpm nx g @nx/react:lib {name}` - generate a react library
* `pnpm nx graph` - show dependency graph of all projects
* `pnpm nx connect-to-nx-cloud` - connect to nx cloud to enable [remote caching](https://nx.app) and make CI faster
  
## Further help

Visit the [Nx Documentation](https://nx.dev) to learn more.


