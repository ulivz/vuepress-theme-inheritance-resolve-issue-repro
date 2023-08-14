# Vuepress Theme Inheritance Resolve Issue Repro

## Step to reproduce

1. install

```bash
pnpm install --prefer-offline
```

2. launch dev server

```bash
NODE_OPTIONS=--openssl-legacy-provider npm run dev
```

3. You'll see following error:

```
client:159 ./node_modules/.pnpm/vuepress-theme-vt@0.13.2/node_modules/vuepress-theme-vt/components/DropdownLink.vue?vue&type=script&lang=js& (./node_modules/.pnpm/cache-loader@3.0.1_webpack@4.46.0/node_modules/cache-loader/dist/cjs.js??ref--0-0!./node_modules/.pnpm/vue-loader@15.10.0_omxcbkrp6io7mc7qb6mfwtlsou/node_modules/vue-loader/lib??vue-loader-options!./node_modules/.pnpm/vuepress-theme-vt@0.13.2/node_modules/vuepress-theme-vt/components/DropdownLink.vue?vue&type=script&lang=js&)
Module not found: Error: Can't resolve '@theme/components/icons/VPIconChevronDown.vue' in '/Users/chenhaoli/Documents/code/docs-next/node_modules/.pnpm/vuepress-theme-vt@0.13.2/node_modules/vuepress-theme-vt/components'
```

