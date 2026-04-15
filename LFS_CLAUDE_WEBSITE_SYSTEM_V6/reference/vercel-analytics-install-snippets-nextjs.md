# Vercel Analytics + Speed Insights Install Snippets (Next.js)

## Vercel Web Analytics
Install:
```bash
npm i @vercel/analytics
```

Add to the root layout:
```tsx
import { Analytics } from '@vercel/analytics/next';

export default function RootLayout({ children }: { children: React.ReactNode }) {
  return (
    <html lang="en">
      <body>
        {children}
        <Analytics />
      </body>
    </html>
  );
}
```

## Vercel Speed Insights
Install:
```bash
npm i @vercel/speed-insights
```

Add to the root layout:
```tsx
import { SpeedInsights } from '@vercel/speed-insights/next';

export default function RootLayout({ children }: { children: React.ReactNode }) {
  return (
    <html lang="en">
      <body>
        {children}
        <SpeedInsights />
      </body>
    </html>
  );
}
```

## Reminder
Claude can usually install the packages and add the components in the repo.
The user may still need to enable the products in the Vercel dashboard.
