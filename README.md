# Replication steps
1. yarn dev - Letting compile finish (open browser to page, let it refresh each time)
2. Uncomment div line in index.css and wait for compile
3. Comment div line in index.css and wait for compile
4. Repeat step 2,3 until Out of memory (Usually 2-3 times)

# Changes made to blog-starter-typescript
- Changed "dev" to use "next dev"
- Updated tailwindcss 
- Added tailwindcss-dark-mode, tailwindcss-text-indent
- Added themes and plugins to tailwind.config.js 