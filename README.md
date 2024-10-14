# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).

## Problem and How I overcame it
The problem came in when I was trying to run the command `deno task dev` the continuous error that was thrown to me was `npm package '@jsr/oak__oak' does not exist.`.
This issue was frustrating for which I tried to use **oak** and **cors** directly from the link.
After a couple of tries, I figured out that the oak/oak14 jrs package was not installed, hence I ran this `npx jsr i @oak/oak@14` in the terminal.

After this everything worked perfectly fine
![Screenshot 2024-10-14 202445](https://github.com/user-attachments/assets/967ae664-9600-4ab4-a631-e4ede7485c98)
