# Image2PDF - Image to PDF Converter

A modern, fast, and secure web application that converts PNG, JPG, and JPEG images to PDF format. Built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🚀 **Lightning Fast**: Convert images to PDF in seconds
- 🔒 **Secure & Private**: Files are processed securely and automatically deleted
- 🎨 **High Quality**: Maintain original image quality in PDF output
- 📱 **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- 🌙 **Dark Mode**: Automatic dark mode support
- 🎯 **Drag & Drop**: Intuitive file upload with drag and drop support
- 📊 **File Preview**: See your images before conversion
- 🆓 **Free to Use**: No registration required

## Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS v4
- **Icons**: Heroicons (SVG)
- **Deployment**: Ready for Vercel deployment

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd img2pdf-saas
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. **Upload Images**: Drag and drop your PNG, JPG, or JPEG files onto the upload area, or click "Choose Files" to browse
2. **Preview**: See your selected images with file information
3. **Convert**: Click "Convert to PDF" to process your images
4. **Download**: Your PDF will be ready for download

## Supported Formats

- **Input**: PNG, JPG, JPEG
- **Output**: PDF
- **File Size**: Up to 10MB per file

## Development

### Project Structure

```
img2pdf-saas/
├── .env                    # Environment variables (Supabase config)
├── .gitignore             # Git ignore rules
├── eslint.config.mjs      # ESLint configuration
├── next.config.ts         # Next.js configuration
├── next-env.d.ts          # Next.js TypeScript definitions
├── package.json           # Project dependencies and scripts
├── package-lock.json      # Locked dependency versions
├── postcss.config.mjs     # PostCSS configuration
├── public/                # Static assets
│   ├── file.svg           # File icon
│   ├── globe.svg          # Globe icon
│   ├── next.svg           # Next.js logo
│   ├── vercel.svg         # Vercel logo
│   └── window.svg         # Window icon
├── README.md              # Project documentation
├── src/                   # Source code
│   └── app/               # Next.js App Router
│       ├── favicon.ico    # Site favicon
│       ├── globals.css    # Global styles
│       ├── layout.tsx     # Root layout
│       └── page.tsx       # Homepage component
└── tsconfig.json          # TypeScript configuration
```

### Environment Setup

Create a `.env` file in the root directory with your Supabase credentials:

```bash
# Supabase Configuration
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url_here
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key_here
```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Deployment

This project is optimized for deployment on Vercel:

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically

## Roadmap

- [ ] Backend API for PDF conversion
- [ ] File compression options
- [ ] PDF page size customization
- [ ] Batch processing
- [ ] User accounts and file history
- [ ] API rate limiting
- [ ] Progress tracking for large files

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is licensed under the MIT License.

## Support

For support, please open an issue on GitHub or contact us at support@image2pdf.com