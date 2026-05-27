# verifikasi signature webhook Midtrans

`sha512(order_id+status_code+gross_amount+server_key)` — bandingkan sama signature_key. Tanpa ini, siapapun bisa POST status 'settlement' palsu.
