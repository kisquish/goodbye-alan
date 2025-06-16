# Au Revoir Alan - Memorial Website

A memorial website for Alan Galwine NANKENG FOZON, hosted on AWS S3 and deployed via GitHub Actions.

## Website Information

- **Name**: Alan Galwine NANKENG FOZON
- **Birth**: October 19, 2008
- **Death**: June 10, 2025
- **Location**: Fotomena, Cameroon

## Technical Details

### Website Structure
- `index.html` - Main memorial page
- `error.html` - Custom 404 error page
- `IMG_8427.jpeg` - Alan's photo

### Deployment
The website is automatically deployed to AWS S3 using GitHub Actions. The deployment process:
1. Uploads website files to S3
2. Enables static website hosting
3. Configures public access
4. Sets up bucket policies

### Access
The website is available at:
- HTTP: http://goodbyealan.s3-website.eu-central-1.amazonaws.com

## Development

### Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/kisquish/goodbye-alan.git
   ```
2. Open `index.html` in your browser to view the website locally

### Deployment Setup
The following secrets need to be configured in GitHub repository settings:
- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`
- `AWS_REGION`
- `S3_BUCKET`
- `CLOUDFRONT_DISTRIBUTION_ID` (optional)

## Future Improvements
- [ ] Add HTTPS support via CloudFront
- [ ] Add custom domain support
- [ ] Implement caching headers
- [ ] Add analytics

## Contributing
This is a memorial website. Please respect its purpose and maintain its dignity.

## License
All rights reserved. 