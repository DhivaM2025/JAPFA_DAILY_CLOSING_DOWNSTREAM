# JAPFA_DAILY_CLOSING_DOWNSTREAM
# OBJECTIVE
1. Ensure that all transaction are recorded within SLA in the SAP. i.e​
   - Cash reconciliation must be done within same day​
   - Bank reconciliation must be done H+1​
2. Minimize backdate transaction in the SAP
# HOW TO USE
1. Pilih file sql yang akan digunakan
2. Copy sql dan paste pada DBeaver
3. Run sql
4. Cek hasil
# ABOUT FILE
1. ID90_SALES_DOC_FLOW : query untuk menampilkan raw data untuk Dashboard#1 : sales doc flow, backdate, customer cod
   - Data diambil dari SO_CREATED_DATE '2025-06-01' sd hari ini, ganti date sesuai dengan kebutuhan pada row 262
3. ID90_SALES_FLOW_QTY_PRICE : query untuk menampilkan raw data untuk Dashboard#1 : sales flow qty & price
4. ID90_CUSTOMER_CREDIT_LIMIT : query untuk menampilkan master data customer credit limit yang di-join dengan customer master data
5. ID90_INVENTORY : query untuk menampilkan raw data inventory meliputi movement type, sloc, qty & amount pada inventory
6. ID7A_SALES_DOC_FLOW : query untuk menampilkan raw data untuk Dashboard#1 : sales doc flow, backdate, customer cod
   - Data diambil dari SO_CREATED_DATE '2025-06-01' sd hari ini, ganti date sesuai dengan kebutuhan pada row 214
