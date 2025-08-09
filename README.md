[README_v4.txt](https://github.com/user-attachments/files/21701397/README_v4.txt)
SAMSON – Ventilkalkylator v4 (leverans)

Filer
-----
1) samson_ventilkalkylator_v4.html
   • En sida (offline) – Vätska, Gas/Ånga (BETA), Produktförslag, Inställningar
   • CRM Webhook (POST JSON) – fyll URL och ev. X-API-Key
   • PDF/CSV/Share/Reset – inbyggt

2) samson_product_library_exact.csv
   • Exempel på bibliotek för exakta produktförslag
   • Fyll Kvs_nom_list med era nominella Kvs (per modell/trim; duplicera rader per DN om ni vill)
   • Lägg datablads-URL

Så använder du
--------------
• Öppna HTML-filen i webbläsare.
• Fyll Q/ΔP/SG + öppning/karakteristik → Kv/Kvs/DN.
• Gas/Ånga (BETA) – ge P1/P2 (abs), T1, molekylvikt, Z. Kv beräknas förenklat (icke-strypt antagen).
• Ladda CSV i fliken Produktförslag för exakta matchningar och länkar.
• Skicka RFQ via e-post eller POSTa till CRM-webhook.

Viktigt
-------
• Gas/Ånga är en förenklad metod. Vid choked (strypt) strömning ger den för låga Kvs. Bekräfta alltid mot IEC 60534-2-1 och produktdatablad.
• Verifiera alltid material, tryckklass, anslutning, temperatur och trim (FL/xT).
