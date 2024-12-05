# test-ns

https://github.com/nsvecaro/test-ns.git

SELECT zaposlenik.id, zaposlenik.ime_prezime
FROM zaposlenik
JOIN evidencija
ON zaposlenik.id=evidencija.zaposlenik
ORDER BY evidencija.broj_sati DESC
