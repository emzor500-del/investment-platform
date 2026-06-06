# InvestHub - Commercial Investment Platform

A professional fintech investment platform built with Next.js, TypeScript, and PostgreSQL.

## Features

### Authentication & Security
- User registration and login
- Email verification
- Password reset functionality
- Two-factor authentication (2FA)
- Session management
- RBAC (Role-Based Access Control)
- Audit logging

### User Management
- Complete user profiles
- Referral system
- Account management
- Activity tracking

### KYC Verification
- Government ID verification
- Selfie verification
- Address verification
- Admin approval system
- Multi-step verification process

### Deposit System
- Bank transfer deposits
- Cryptocurrency deposits
- Admin-configurable payment methods
- Payment proof upload
- Transaction ID tracking
- Deposit status management (Pending, Approved, Rejected)
- Deposit history

### Investment System
- Multiple investment plans
- Daily ROI plans
- Weekly ROI plans
- Monthly ROI plans
- Fixed ROI plans
- Compound investment option
- Investment history
- Profit tracking
- Real-time profit calculation

### Withdrawal System
- Withdrawal requests
- Admin approval workflow
- Bank and crypto withdrawals
- Withdrawal history
- Status tracking
- Processing fees

### Customer Support
- Support ticket system
- Live chat functionality
- File attachment support
- Priority system (Low, Medium, High, Urgent)
- Admin support dashboard
- Ticket history

### Admin Dashboard
- Dashboard analytics
- User management
- Deposit management and approval
- Withdrawal management and approval
- Investment plan management
- KYC verification management
- Support ticket management
- Website content management
- Notification management
- Bank account configuration
- Crypto wallet configuration

## Tech Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS
- **Database**: PostgreSQL
- **ORM**: Prisma
- **Authentication**: NextAuth
- **Forms**: React Hook Form + Zod
- **State Management**: Zustand
- **Real-time**: Socket.IO
- **Charts**: Recharts
- **UI Components**: Custom + React Icons
- **Animations**: Framer Motion
- **Email**: Nodemailer
- **File Upload**: Cloudinary
- **Caching**: Redis

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL 14+
- Redis (optional, for caching)

### Installation

1. Clone the repository
```bash
git clone https://github.com/emzor500-del/investment-platform.git
cd investment-platform
```

2. Install dependencies
```bash
npm install
```

3. Setup environment variables
```bash
cp .env.example .env.local
```

4. Setup database
```bash
npm run prisma:migrate
```

5. Start development server
```bash
npm run dev
```

## Development

### Running Migrations
```bash
npm run prisma:migrate
```

### Building for Production
```bash
npm run build
npm run start
```
