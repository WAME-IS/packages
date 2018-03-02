# Packages

## Manual build a packages
### Steps for developers

1. Clone this repository
2. Install Satis: `composer create-project composer/satis --keep-vcs`
3. Build a repository: `php satis/bin/satis satis.json public`
4. Upload content of `/public` directory to **packages.wameis.org** ftp (to `/public_html` directory)