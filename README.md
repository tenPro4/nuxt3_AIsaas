## Startup
```
npx nuxi@latest init <project-name>
npm install @nuxtjs/supabase @supabase/auth-ui-shared @nuxtbase/auth-ui-vue -D
```

Install prisma(Postgres)
```
npm i prisma -D
npx prisma init

```

## Key Feature
- [Shadcn UI](https://www.shadcn-vue.com/docs/installation/nuxt.html)
- [Auth UI](https://github.com/nuxtbase/auth-ui-vue)
- [Superbase](https://supabase.com/). Check out the [documentation](https://supabase.nuxtjs.org/get-started) for Nuxt3 environment.
- [OpenAi](https://openai.com/)
- [Repicate](https://replicate.com/) : audio and video library
- [Stripe](https://stripe.com/en-my)
- [Crisp](https://crisp.chat/en/) Central of manage online conversation | online help desk

## Notes
- utils(index.ts) path dont need to import(Need build first)
- await refreshNuxtData('userData')
```vue
const { data: user, pending } = await useFetch('/api/user', {
  key: 'userData',
});
```
