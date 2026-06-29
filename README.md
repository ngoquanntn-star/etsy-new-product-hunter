# Etsy New Product Hunter

## Chạy local
```bash
npm install
cp .env.example .env.local
npm run dev
```

## Deploy Vercel
1. Upload project lên GitHub.
2. Import repository vào Vercel.
3. Vào Settings → Environment Variables.
4. Thêm `ETSY_API_KEY` = `keystring:shared_secret`.
5. Deploy.

## Ghi chú
App dùng Etsy Open API v3 endpoint `/v3/application/listings/active`, sort theo `created desc`.
