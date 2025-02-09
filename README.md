# Portfolio Template

This is a [Next.js](https://nextjs.org) portfolio template bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

### 1. Fork and Clone

1. Fork this repository by clicking the "Fork" button in the top-right corner
2. Clone your forked repository:

```bash
git clone https://github.com/YOUR_USERNAME/portfolio.git
cd portfolio
```

### 2. Install Dependencies

Install the required dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### 3. Add Your Template

1. Navigate to `app/page.tsx`
2. Replace the existing content with your Smartfolio-generated template
3. Customize the content, styles, and components as needed

### 4. Development

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see your portfolio.

### 5. Deploy on Vercel

#### Option 1: Deploy through Vercel Website (Recommended)

1. Create a [Vercel account](https://vercel.com/signup) if you haven't already
2. Go to [Vercel's New Project page](https://vercel.com/new)
3. Import your GitHub repository
4. Click "Deploy"
5. Wait for deployment to complete
6. Your portfolio will be live at `your-project-name.vercel.app`

#### Option 2: Deploy using Vercel CLI

1. Install Vercel CLI:

```bash
npm install -g vercel
```

2. Deploy your portfolio:

```bash
vercel
```

### Custom Domain (Optional)

To add your own domain:

1. Go to your project on Vercel
2. Click "Settings" → "Domains"
3. Add your domain and follow the DNS configuration instructions

## Customization

This project uses:

- [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) for optimized fonts
- [Tailwind CSS](https://tailwindcss.com) for styling
- [TypeScript](https://www.typescriptlang.org) for type safety

## Learn More

To learn more about the technologies used:

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Vercel Documentation](https://vercel.com/docs)

## Need Help?

If you encounter any issues:

1. Check the [Next.js GitHub repository](https://github.com/vercel/next.js)
2. Join the [Vercel Community](https://vercel.com/community)
3. Search for solutions on [Stack Overflow](https://stackoverflow.com/questions/tagged/next.js)

## Common Issues & Solutions

1. **Build Errors**: If you encounter build errors after adding your template:

   - Check for missing dependencies
   - Ensure all imports are correct
   - Verify TypeScript types are properly defined

2. **Styling Issues**: If styles aren't applying correctly:

   - Make sure Tailwind classes are correct
   - Check if global CSS is imported in `layout.tsx`
   - Verify PostCSS configuration

3. **Deployment Issues**: If deployment fails:
   - Check Vercel build logs
   - Ensure all environment variables are set
   - Verify project compatibility with Vercel

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
