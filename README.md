# School Management Dashboard
<img src="./public/img1.png" alt="Dashboard-1" width="600" />
<img src="./public/img2.png" alt="Dashboard-2" width="600" />

# This project uses technology: 
 - Next
 - Postgresql
 - Clerk
 - Cloudinary
 - Tailwindcss
## Before start
1. Setup environment variables.
```
NEXT_PUBLIC_API_URL=you_host
DATABASE_URL=postgresql://[your_user]:[your_password]@[hosr]:5432/[name_db]
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publickClerk_key
CLERK_SECRET_KEY=you_secret_key
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary
```
## Getting Started

2. You can run this project using Docker. Just go to the project folder and run the command
```
docker-compose up -d
```

3. After installation, you need to fill the database with data. Run the command
```
npx prisma db seed
```
4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Note
To run this project you must register accounts in these services and get secret keys.

 - Clerk
 - Cloudinary


