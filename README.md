
<!DOCTYPE html>
<html>
<head>
    <title>SEBA YANGIN - WATERMIST BAKIM FORMU</title>
    <style>
        body { font-family: sans-serif; margin: 0; padding: 20px; box-sizing: border-box; font-size: 12px; }
        .container { width: 100%; max-width: 800px; margin: auto; padding: 20px; border: 1px solid #000; }
        .header { text-align: center; margin-bottom: 20px; }
        .header h1 { font-size: 16px; margin: 0; font-weight: bold; }
        .header p { font-size: 14px; margin: 0; }
        .info-table, .checklist-table { width: 100%; border-collapse: collapse; margin-bottom: 20px; }
        .info-table th, .info-table td, .checklist-table th, .checklist-table td { border: 1px solid #000; padding: 5px; text-align: center; vertical-align: middle; }
        .info-table th { background-color: #f2f2f2; font-weight: bold; }
        .info-table input[type="text"] { width: 95%; border: none; padding: 2px; }
        .checklist-table td:nth-child(2) { text-align: left; }
        .checklist-table input[type="radio"] { margin: 0; }
        .signature-section { display: flex; justify-content: space-between; margin-top: 30px; }
        .signature-block { width: 45%; }
        .signature-block canvas { border: 1px solid #000; width: 100%; height: 100px; }
        .button-container { text-align: center; margin-top: 20px; }
        button { padding: 10px 20px; font-size: 14px; cursor: pointer; }
        @media print { .button-container, .no-print { display: none; } }
    </style>
</head>
<body>
    <div class="container" id="form-container">
        <div class="header">
            <p>SSEBA YANGIN SÖNDÜRME SİSTEMLERİ</p>
            <p>seba teknik TSE-HYB 75 12873 34-HY8-15806</p>
            <h1>WATERMIST YANGIN POMPASI BAKIM FORMU</h1>
        </div>

        <table class="info-table">
            <thead>
                <tr>
                    <td colspan="4" style="text-align: left; border: none; padding-left: 0;">
                        <span style="font-weight: bold;">Firma Adı:</span> <input type="text" style="width: 250px;">
                        <span style="font-weight: bold; margin-left: 50px;">TARİH:</span> <input type="text" style="width: 150px;">
                    </td>
                </tr>
                <tr>
                    <th>Pompa Bilgisi</th>
                    <th>JOKEY POMPA</th>
                    <th>I. DİZEL POMPA</th>
                    <th>II. DİZEL POMPA</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>Pompa Modeli</td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td></tr>
                <tr><td>Pompa Seri No</td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td></tr>
                <tr><td>Motor modeli</td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td></tr>
                <tr><td>Motor Seri no</td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td></tr>
                <tr><td>K.Panosu Modeli</td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td></tr>
                <tr><td>K.Panosu Seri No</td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td></tr>
                <tr><td>Pompa Basınç Değerleri</td><td><input type="text"></td><td><input type="text"></td><td><input type="text"></td></tr>
            </tbody>
        </table>

        <table class="checklist-table">
            <thead>
                <tr>
                    <th style="width:5%"></th>
                    <th style="width:60%"></th>
                    <th style="width:10%">EVET</th>
                    <th style="width:10%">HAYIR</th>
                    <th style="width:15%">NOTLAR</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>1</td><td>Test için depoda gerekli su mevcut mu?</td><td><input type="radio" name="check1"></td><td><input type="radio" name="check1"></td><td rowspan="16"><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>2</td><td>Emiş ve basma vanaları açık mı?</td><td><input type="radio" name="check2"></td><td><input type="radio" name="check2"></td></tr>
                <tr><td>3</td><td>Hava atma ventili kontrol edildi mi?</td><td><input type="radio" name="check3"></td><td><input type="radio" name="check3"></td></tr>
                <tr><td>4</td><td>Kaide ankraj vidası ve grout beton ile sabitlendi mi?</td><td><input type="radio" name="check4"></td><td><input type="radio" name="check4"></td></tr>
                <tr><td>5</td><td>Gresörlüklerine gres basıldı mı?</td><td><input type="radio" name="check5"></td><td><input type="radio" name="check5"></td></tr>
                <tr><td>6</td><td>Kaplin bağlantısı kontrol edildi mi?</td><td><input type="radio" name="check6"></td><td><input type="radio" name="check6"></td></tr>
                <tr><td>7</td><td>Basınç hissetme hattı kontrol edildi mi?</td><td><input type="radio" name="check7"></td><td><input type="radio" name="check7"></td></tr>
                <tr><td>8</td><td>Akü suları yeterli ve Kutup başları temiz mi?</td><td><input type="radio" name="check8"></td><td><input type="radio" name="check8"></td></tr>
                <tr><td>9</td><td>Motor ısıtıcısı devrede mi?</td><td><input type="radio" name="check9"></td><td><input type="radio" name="check9"></td></tr>
                <tr><td>10</td><td>Motor soğutma hattı vanalarından su geliyor mu?</td><td><input type="radio" name="check10"></td><td><input type="radio" name="check10"></td></tr>
                <tr><td>11</td><td>Yakıt seviyesi yeterli mi? Yakıt besleme vanası açık mı?</td><td><input type="radio" name="check11"></td><td><input type="radio" name="check11"></td></tr>
                <tr><td>12</td><td>Motor yağı değiştirildi mi?</td><td><input type="radio" name="check12"></td><td><input type="radio" name="check12"></td></tr>
                <tr><td>13</td><td>Motor yağ filtresi değiştirildi mi?</td><td><input type="radio" name="check13"></td><td><input type="radio" name="check13"></td></tr>
                <tr><td>14</td><td>Motor yakıt filtresi değiştirildi mi?</td><td><input type="radio" name="check14"></td><td><input type="radio" name="check14"></td></tr>
                <tr><td>15</td><td>Motor hava filtresi değiştirildi mi?</td><td><input type="radio" name="check15"></td><td><input type="radio" name="check15"></td></tr>
                <tr><td>16</td><td>Motor için antifrizli su yeterli mi?</td><td><input type="radio" name="check16"></td><td><input type="radio" name="check16"></td></tr>
                <tr><td>17</td><td>Motor ve k.panosu elektrik bağlantıları kontrol edildi mi?</td><td><input type="radio" name="check17"></td><td><input type="radio" name="check17"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>18</td><td>Kontrol panosu temizliği yapılmış mı?</td><td><input type="radio" name="check18"></td><td><input type="radio" name="check18"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>19</td><td>Çalıştı ve arıza bilgisi uzaktan izleniyor mu?</td><td><input type="radio" name="check19"></td><td><input type="radio" name="check19"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>20</td><td>Motor üzerindeki manuel start çalışıyor mu?</td><td><input type="radio" name="check20"></td><td><input type="radio" name="check20"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>21</td><td>Otomatik olarak devreye giriyor mu?</td><td><input type="radio" name="check21"></td><td><input type="radio" name="check21"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>22</td><td>Otomatik olarak devreden çıkıyor mu?</td><td><input type="radio" name="check22"></td><td><input type="radio" name="check22"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>23</td><td>Motor yağ basıncı değeri uygun mu?</td><td><input type="radio" name="check23"></td><td><input type="radio" name="check23"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>24</td><td>Motor istenilen değere ulaştı mı?</td><td><input type="radio" name="check24"></td><td><input type="radio" name="check24"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>25</td><td>Salmastra yataklarından soğutma suyu geliyor mu?</td><td><input type="radio" name="check25"></td><td><input type="radio" name="check25"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>26</td><td>Akü şarj redresörleri çalışıyor mu?</td><td><input type="radio" name="check26"></td><td><input type="radio" name="check26"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>27</td><td>Flow (debi) testi yapıldı mı?</td><td><input type="radio" name="check27"></td><td><input type="radio" name="check27"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>28</td><td>Çalışma saati kontrol edildi mi?</td><td><input type="radio" name="check28"></td><td><input type="radio" name="check28"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>29</td><td>Pompa Odası min. 4 °C olması gerektiği bilgisi verildi mi?</td><td><input type="radio" name="check29"></td><td><input type="radio" name="check29"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
                <tr><td>30</td><td>Pompada herhangi bir sorun var mı?</td><td><input type="radio" name="check30"></td><td><input type="radio" name="check30"></td><td><textarea style="width: 95%; height: 95%; border: none; resize: none;"></textarea></td></tr>
            </tbody>
        </table>

        <div style="margin-top: 20px;">
            <b>AÇIKLAMA;</b>
            <textarea style="width: 100%; height: 80px; border: 1px solid #000; box-sizing: border-box;"></textarea>
        </div>

        <div class="signature-section">
            <div class="signature-block">
                <b>SEBA TEKNİK</b><br>
                ADI SOYADI: <input type="text" style="width: 95%; border: none; border-bottom: 1px solid #000;"><br>
                İMZA: <canvas id="signature-canvas-seba"></canvas>
            </div>
            <div class="signature-block">
                <b>FİRMA YETKİLİSİ</b><br>
                AD SOYAD: <input type="text" style="width: 95%; border: none; border-bottom: 1px solid #000;"><br>
                İMZA: <canvas id="signature-canvas-firma"></canvas>
            </div>
        </div>

        <div class="footer">
            <p>SEBA TEK. TES. SİS.SAN. TİC.A.Ş. AK PINAR MH. MALKOÇOĞLU CD.NO:57/A SANCAKTEPE/İST TEL:0216 498 70 75 info@sebateknik.com</p>
        </div>
    </div>
    
    <div class="button-container no-print">
        <button id="save-pdf">PDF Olarak Kaydet</button>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/signature_pad/1.5.3/signature_pad.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>

    <script>
        // İmza canvas'larının başlatılması
        const canvasSeba = document.getElementById('signature-canvas-seba');
        const signaturePadSeba = new SignaturePad(canvasSeba);
        const canvasFirma = document.getElementById('signature-canvas-firma');
        const signaturePadFirma = new SignaturePad(canvasFirma);

        // Canvas boyutlarını otomatik ayarlama
        function resizeCanvas() {
            const ratio = Math.max(window.devicePixelRatio || 1, 1);
            canvasSeba.width = canvasSeba.offsetWidth * ratio;
            canvasSeba.height = canvasSeba.offsetHeight * ratio;
            canvasSeba.getContext('2d').scale(ratio, ratio);
            canvasFirma.width = canvasFirma.offsetWidth * ratio;
            canvasFirma.height = canvasFirma.offsetHeight * ratio;
            canvasFirma.getContext('2d').scale(ratio, ratio);
            signaturePadSeba.clear();
            signaturePadFirma.clear();
        }
        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();

        // PDF oluşturma fonksiyonu
        document.getElementById('save-pdf').addEventListener('click', function () {
            const formElement = document.getElementById('form-container');

            html2canvas(formElement, {
                scale: 2, // Görüntü kalitesini artırır
                useCORS: true,
                logging: true
            }).then(canvas => {
                const imgData = canvas.toDataURL('image/png');
                const { jsPDF } = window.jspdf;
                const pdf = new jsPDF('p', 'mm', 'a4');
                const imgWidth = 210; 
                const pageHeight = 297; 
                const imgHeight = canvas.height * imgWidth / canvas.width;
                let heightLeft = imgHeight;
                let position = 0;

                pdf.addImage(imgData, 'PNG', 0, position, imgWidth, imgHeight);
                heightLeft -= pageHeight;

                while (heightLeft >= 0) {
                    position = heightLeft - imgHeight;
                    pdf.addPage();
                    pdf.addImage(imgData, 'PNG', 0, position, imgWidth, imgHeight);
                    heightLeft -= pageHeight;
                }
                
                pdf.save('bakim-formu.pdf');
            });
        });
    </script>
</body>
</html>
