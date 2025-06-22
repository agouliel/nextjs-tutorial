## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Deployment
``kill `ps -ax | grep npm | grep -v grep | awk '{print $1}'` >/dev/null 2>&1``   
```ssh mini << EOF
cd /Users/Shared/src/react_src/nextjs
npm run build
nohup npm run start </dev/null >/dev/null 2>&1 &
EOF```
