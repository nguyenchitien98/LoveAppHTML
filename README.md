Cách tự build file .exe
1. Cài Node.js từ: https://nodejs.org
2. Cài electron-packager: npm install -g @electron/packager
3. Mở terminal tại thư mục này và chạy:

npm install
npx electron-packager . LoveApp --platform=win32 --arch=x64 --out=dist --overwrite
