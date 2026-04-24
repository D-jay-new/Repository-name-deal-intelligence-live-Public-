This is the package to make your app live on a public web page.

Fastest route:
1. Upload this folder to GitHub.
2. Open Render.com.
3. New + → Web Service.
4. Connect your GitHub repo.
5. Build Command:
   pip install -r requirements.txt

6. Start Command:
   uvicorn main:app --host 0.0.0.0 --port $PORT

7. Add Environment Variable:
   KEEPA_API_KEY = your_actual_keepa_key

8. Deploy.
9. Open the Render URL from phone/laptop.

No phone installation needed.
