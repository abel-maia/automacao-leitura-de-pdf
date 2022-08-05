<h1 align='center'>Sistema de Automação de Renomeação de PDFs

<h2>Como começou?
 <h5>Eu trabalho como jovem aprendiz na minha empresa, eu tinha um trabalho designado somente a mim, renomear milhares de PDfs por dia, mas eu tinha preguiça de efetuar esse trabalho, eu fazia quase chorando. Então eu tive a brilhante ideia, por que não fazer uma automação em python para poder fazer isso por mim? É meio chato fazer o mesmo processo todo dia..
<h2>Por que o python?
  <h5>Eu poderia ultilizar dezenas de linguagens diferentes para isso, mas eu escolhi o python por 3 fatores:
   <ol>
     <li>É facil de usar.</li> 
     <li>Tem muitas bibliotecas para me ajudar.</li> 
     <li>A empresa onde eu trabalho aprova o python.</li> 
   </ol>
<h2>Como funciona o sitema?
 <h5>Antes de entendermos sobre o sistema em si, vamos entender o que eu fazia manualmente:
  <ol>
   <li>Eu tinha uma lista com mais de 500 Pdfs</li>
   <img src="https://lh3.googleusercontent.com/IO4EulOMSa720aygXJ-BFbF0F54EcCY9Yl10HIfaVyAWxGMDv4BGBMTmO7Q-4zqNBAuierYsmKZcW61c1RSvFa4r3N-abyW9e7FEyizs9Wc9qd4BG9id92-w8e60rVKcxfvaormCRptJ5uBMPvd3_RqPRaBZGenMI_X0o9HWDEkoMogtUjuK9zr08qjWOGhF4KdyPRxA71LOEMEc6YHBkDtqeTQsFnqxaEA5HMOFyqgEBsX4Y56rq56bmZsEHmJ-o0l03oD8qIXHrEcfR2RMZ5tDMjLypSA7MVcSYYHxwUnfcspnUF6ktsM0OBVd2eN45jkfQ39YZLsXtBasvIx3kWiOo20dG_hXlq38-XaNlN60NRuhm69sNBtDq1GFZ65N8-1RwGM7QUK6UePPhn9F00hWSenBn47mTudMTuNMwtipF02FUEXdW1WiZPDhhhOw63Bj3IFV7OyMvgdhFSlx5Pe2hnagvpgSR4BciRyAod_ljQDzh2OAsnsKCeg1ksCOp2i9LaJjkIH_NyTCIOOvHlf6ku79nZ5qvzjRjvSwyUBV08UzpeIdM7fZWxbHGsNk_jc6vge4EjDZGPoNGzqHbGrcRTNvhxU2K-cQSlFoQlm7dlgJyf9oa6aBzSjpDY-TMWpPLT_Qnysa2-ZmIlijP3rJ095GcIIeW7q2b1BtWWdbSYnPaVwkBXCIR7ndMNOJsDpl0mY81lpnVcGXLx-4xfMVY8wNgbyN4CJPHy1OC3HN2aFXxptJVZ9as06AKb56Pi1ger88d0u-moY5fYejQuKt7Y_JciY=w473-h96-no?authuser=0"</img>
   <li>Eu abria cada um deles separadamente</li>
   <li>Eu pegava uma informação que tinha nele dava Ctrl+C</li>
   <img src="https://lh3.googleusercontent.com/0IrcFIgrUqzXjz_C3Ou71K-u0VWQwdISk8EKxu5F_pYcSXQ95S4JwHMaHhrAbYuIULwDo0D2cOZppSAul8OHdn6IQznO-Qkj4SOCM6RI5XBqY82sHcXnliUg7iqzsR-0MJqnGvUnP3sQWPxJk4x6qnb0S4j2GBBPQjIYU3bbsb6kbZJuvJ-k9-t4CVDNKAaTwftnsXP9sgMKVBPrad3mZc_nCny5pqRNjEVwY0-BaVgXX5_OGeflxyftlPuxP9yMR8PHjOxbKTPV8tE7-H_ubvnoyvzwf66d0ORipUVoPT07ExmM-jZmSPlaYtI-RwpokcJLEoxZZoJmrhRgdE2UrNzCFnNvMO7pOQzWtU0jDiV-6uFtu1c1xyz98UIAYYq384c4awWvVn5gX5tCOXIXZhAYCtaea0pIn5op4YYJsPLuwYBL_wmKO8tCp5f0W_HPklOgfy58uoDNT4hRUPk5x0bBKG-NUQCT1zMrZLupBMMJxs0e6pI0NBWdD9eAAg9fVXtm_gqRBdeYvKYyjygD4AFND3bpAbqj0BQu7YcWuj0TutwwlW4i3y5IZcqVaDBf_FSLDEDOvhO1FM7F5nKg62jMrmi1MB4p59bRpZbX2ErzBc630zIjJJDPc5r8aEVwCJOdYxFjuA1YIPL3nYQjHEE2cwtWv6Sz9iB-pu7SxX4e7o9HM38wo4gXZtyBAUcRQvSMwwa1OABELPh-5Ex_naz0h40dFQ3zDe9vzec4eCjv6QD5QiNdwEv0YFWyfYICk3laiIk3dXYZ4g1MJ5BCmUu4Nlubmrk=w663-h44-no?authuser=0">
   <li>Eu renomeava o Pdfs com o cod dele + o Ctrl+V</li>
   <li>E Então eu concluia 1 Pdf</li>
   <img src="https://lh3.googleusercontent.com/Ntbab8mYGjUQK2EQcPqhMOcNzcAJPqRgWEkAgsl7dSf4jsqbbL-nxhpvMYj7IPLidyOCmULUsN8aNpLx_NAuy2Od9uOuVxCgIFy5jSol9H_uexM_-oGic1H6E9Gwh0ZmHJQbqILol4c_QcWRn97MCsGr_gZSM0Y2km3gzt6Vbtt_9i5PhqJbMmC-cexqxeq7P3kBEG9c6h7nkmivnT3H-IKWpBkCHlhHr-a36dnZQnjfp36ywevbOaf3e1SDeYRcU39cSi_9YdcY_UM4HaXVy6yN17P5Mlnhm1IMHUjyvvIxOFwSVrzT5n8RFbPCzwtDhUH3Ptdzo7b8zgEoX1qg9DBdjshQy5jNRJ_LLS7FKyqfX9yhYqMIHM_c4TcvKnnqaBvtFfdqV7iqszSdRIHjV_PoLAakecqnzs-n0uw-DHA7VtI4aH3jAVzSzreL8oVTKAn2Ef_WGEONoD3_ku4Xm1OiIpJ04i1fby5Vh8XqMQmCFYZAZ25TU6QEcyYbsNSlqIjOciT7TRoY97PN6f-bSq1jlDlozYX-iudos91h7MxTiPgiKwWS-jOvTkW04iTTURCrS9ETWH7z4npZAE45-vm7YUdQ74-HJqy8OXcTvib1Gp8CgSgUJwQYZcc04RCjUADAQP_-eDvVqzxjeqEzQG3X1LVMod3HPBBB8tHkSAd6rxj6GWx0mjIaHohsIBHy1p7RxQKrM1v6X447GGekXkrsA5vDIRSaCOm5xCl8zmOJrat2aij07IPnMf1aGkR45BsJ901gf9_Hbatqvmf2rgGnClMJ4ZY=w469-h38-no?authuser=0">
  </ol>
 <h5>Dá pra ver que isso era muito trabalhoso
