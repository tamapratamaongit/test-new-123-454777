# Test New 123

A website project with Pages, Blog, SEO, Analytics

## 📋 Getting Started

This project was scaffolded from the official Payload CMS **website** template.

### ⚠️ Important: Fetch Template Files

This repository was initialized with minimal scaffolding. To get the complete template, you need to fetch files from the official Payload CMS repository.

#### 🚀 Quick Setup (Recommended)

```bash
# 1. Clone the Payload repository
git clone https://github.com/payloadcms/payload.git payload-official-template

# 2. Copy template files to your project
cp -r payload-official-template/templates/website/* .

# 3. Remove the temporary clone
rm -rf payload-official-template

# 4. Install dependencies
pnpm install

# 5. Set up environment
cp .env.example .env.local
# Edit .env.local with your configuration

# 6. Start development server
pnpm dev
```

### 📁 Manual Setup (Alternative)

1. Visit: https://github.com/payloadcms/payload/tree/main/templates/website
2. Download all files from that directory
3. Copy them to your project root
4. Follow steps 4-6 above

### 🔧 Development

After setting up the template:

```bash
# Start dev server
pnpm dev

# Build for production
pnpm build

# Start production server
pnpm start

# Database commands
pnpm db:generate
pnpm db:migrate
```

### 📚 Template Details

- **Template Name**: website
- **Official Repository**: https://github.com/payloadcms/payload
- **Template Path**: `templates/website`
- **Framework**: Next.js + Payload CMS
- **Database**: PostgreSQL
- **ORM**: Drizzle

### 📖 Resources

- [Payload CMS Docs](https://payloadcms.com/docs)
- [Next.js Docs](https://nextjs.org/docs)
- [Template Repository](https://github.com/payloadcms/payload/tree/main/templates/website)

### 🆘 Troubleshooting

**Issue: Files not found after cloning?**
- Make sure you're in the correct project directory
- Verify the template path: `ls templates/website`

**Issue: Dependencies not installing?**
- Clear node_modules: `rm -rf node_modules`
- Reinstall: `pnpm install`

**Issue: Database connection failing?**
- Check `.env.local` is properly configured
- Ensure PostgreSQL is running locally or accessible

### 📝 Next Steps

1. Fetch the complete template files using the Quick Setup section above
2. Configure your database connection in `.env.local`
3. Review the template's documentation
4. Start building your project!
