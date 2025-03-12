
cd C:\Users\Public\Documents\projects\ts-debug

npm create astro@latest 

npx astro add react

import { defineConfig } from 'astro/config';
import react from '@astrojs/react';

export default defineConfig({
  // ...
  integrations: [react()],
});

## How to
Click "Run Debug" button
play Development Server
then
play "Chrome against localhost"
