# $TEOS Egypt Mobile Mining App

Repository created autonomously by Elmahrosa International

Welcome to the official repository for the **$TEOS Egypt Mobile Mining App**, a culturally significant cryptocurrency application developed exclusively by **Elmahrosa International**. This app integrates **Solana blockchain** technology with gamified mining and Egyptian cultural education, designed for the **Pi Network community** with a **Global Community Value (GCV) of $314,159** in $TEOS tokens, capped at **500M $TEOS** and limited to the first **100,000 Pi Network Pioneers**.

## Overview

The $TEOS app engages users through gamified token mining, interactive Egyptian history quizzes, meme creation tools, and decentralized governance, promoting cultural preservation. Key features include:

- **Gamified Mining**: Earn $TEOS tokens via one-click mining (50 $TEOS/day for standard users, 100 $TEOS/day for premium subscribers).
- **Cultural Education**: Interactive quizzes and 30-second VR previews of Egyptian historical sites with token rewards.
- **Pi Network Integration**: Seamless registration using Pi Network accounts for GCV eligibility.
- **Subscription Model**: **$5 USD/month** premium subscription, exclusively by Elmahrosa, for enhanced mining and content access.
- **GCV $314,159 Incentive**: A $314,159 $TEOS token bonus pool (up to 500M $TEOS) for the first 100,000 Pi Network Pioneers subscribing within 3 months.
- **Gift Limits**: No 50 or 100 $TEOS token gifts (e.g., welcome or engagement bonuses) after 100,000 Pioneers.
- **Governance**: Quadratic and conviction voting for proposals (500k $TEOS staking threshold).
- **Meme Creation**: Egyptian-themed meme tools with contest rewards.
- **Security**: AES-256 encryption, 2FA via Auth0, reCAPTCHA v3, and ML-based anti-bot detection.

Built with React Native for iOS/Android, Solana’s SPL Token Standard, and Rust smart contracts, the app surpasses competitors like Pi Network, Bee Network, and Sidra Chain by blending entertainment, education, and cultural significance.

## Repository Structure

```
├── src/                          # Main application source code
│   ├── components/              # Reusable React Native components
│   ├── screens/                 # Application screens
│   ├── services/                # Business logic and API services
│   ├── navigation/              # Navigation configuration
│   ├── context/                 # React context providers
│   ├── i18n/                    # Internationalization
│   └── store/                   # State management
├── contracts/                   # Smart contract source code
├── CONTRIBUTING.md              # Contribution guidelines
├── CODE_OF_CONDUCT.md          # Code of conduct
├── SECURITY.md                 # Security policy
└── LICENSE                     # License information
```

## Getting Started

### Prerequisites

- **Node.js**: v18.x LTS
- **Yarn**: v1.22+
- **Rust**: v1.70+
- **Solana CLI**: v1.16+
- **React Native CLI**: Latest
- **Xcode**: v15+ (iOS)
- **Android Studio**: 2023.1+ (Android)
- **Docker**: v24.0+
- **MongoDB**: v6.0+
- **Redis**: v7.0+
- **Stripe CLI**: For USD payments

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Elmahrosa/TEOS-Egypt-Mobile-Mining-App.git
cd TEOS-Egypt-Mobile-Mining-App
```

2. Install dependencies:
```bash
yarn install
```

### Smart Contract Deployment

Deploy the smart contracts to Solana:
```bash
solana program deploy target/deploy/teos_egypt_token.so
```

### Running the Mobile App

For iOS:
```bash
cd mobile-app
yarn ios
```

For Android:
```bash
cd mobile-app
yarn android
```

### Testing

Run smart contract tests:
```bash
cd contracts
anchor test
```

Run mobile app tests:
```bash
cd mobile-app
yarn test
```

### Deployment

Deploy the backend services:
```bash
node scripts/deploy.js
```

Build for production:
```bash
cd mobile-app
yarn build:ios
yarn build:android
```

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before submitting pull requests.

## Security

For security concerns, please review our [Security Policy](SECURITY.md).

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.