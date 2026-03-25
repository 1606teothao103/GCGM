<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Bảng tính Gà Mẹ Gà Con</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; display: flex; flex-direction: column; align-items: center; padding: 30px; background-color: #eceff1; }
        .container { background: white; padding: 25px; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); width: 450px; }
        h2 { text-align: center; color: #333; margin-bottom: 25px; }
        .row { display: flex; justify-content: space-between; margin-bottom: 15px; }
        .box { flex: 1; margin: 0 5px; text-align: center; border: 1px solid #ddd; padding: 10px; border-radius: 8px; }
        .box-highlight { background-color: #f8f9fa; border: 2px solid #007bff; }
        label { display: block; font-size: 13px; font-weight: bold; margin-bottom: 5px; color: #555; }
        input { width: 80%; padding: 8px; text-align: center; font-size: 18px; border: 1px solid #ccc; border-radius: 4px; outline: none; }
        .btn-group { display: flex; gap: 10px; margin-top: 20px; }
        button { flex: 1; padding: 12px; font-size: 16px; font-weight: bold; cursor: pointer; border: none; border-radius: 6px; transition: 0.2s; color: white; }
        .btn-nhap { background-color: #6c757d; }
        .btn-nhap:hover { background-color: #5a6268; }
        .btn-tinh { background-color: #28a745; }
        .btn-tinh:hover { background-color: #218838; }
        #result-box { margin-top: 25px; padding: 15px; border-radius: 8px; text-align: center; font-size: 22px; font-weight: bold; min-height: 30px; background: #fff3cd; color: #856404; border: 1px solid #ffeeba; }
        .highlight-red { color: #d9534f; }
    </style>
</head>
<body>

<div class="container">
    <h2>Gà Mẹ & Gà Con</h2>

    <div class="row">
        <div class="box">
            <label>SỐ THỨ TỰ</label>
            <input type="number" id="stt" value="1">
        </div>
        <div class="box">
            <label>GÀ MẸ (Trên)</label>
            <input type="number" id="ga_me_goc" value="0">
        </div>
        <div class="box">
            <label>GÀ CON (Trên)</label>
            <input type="number" id="ga_con_goc" value="0">
        </div>
    </div>

    <div class="row">
        <div class="box box-highlight">
            <label>TÂM ĐIỂM GÀ CON</label>
            <input type="number" id="tp_ga_con" value="0" style="color: #007bff;">
        </div>
        <div class="box box-highlight">
            <label>TÂM ĐIỂM GÀ MẸ</label>
            <input type="number" id="tp_ga_me" value="0" style="color: #eeaa00;">
        </div>
    </div>

    <div class="btn-group">
        <button class="btn-nhap" onclick="nutNhap()">NHẬP</button>
        <button class="btn-tinh" onclick="nutBatDau()">BẮT ĐẦU</button>
    </div>

    <div id="result-box">Đang chờ tính toán...</div>
</div>

<script>
    // --- NÚT NHẬP: Xử lý tự động hóa nhảy số ---
    function nutNhap() {
        let stt = parseInt(document.getElementById('stt').value);
        let gaMeGoc = parseInt(document.getElementById('ga_me_goc').value);
        let gaConGoc = parseInt(document.getElementById('ga_con_goc').value);
        let tpGaCon = parseInt(document.getElementById('tp_ga_con').value);
        let tpGaMe = parseInt(document.getElementById('tp_ga_me').value);

        // Tăng STT lên 1
        document.getElementById('stt').value = stt + 1;

        // So sánh tâm điểm để cộng thêm 1
        if (tpGaCon > tpGaMe) {
            document.getElementById('ga_con_goc').value = gaConGoc + 1;
        } else if (tpGaCon < tpGaMe) {
            document.getElementById('ga_me_goc').value = gaMeGoc + 1;
        }
        
        document.getElementById('result-box').innerText = "Đã cập nhật số liệu!";
        document.getElementById('result-box').style.color = "#6c757d";
    }

    // --- NÚT BẮT ĐẦU: Xử lý công thức tính kết quả ---
    function nutBatDau() {
        let stt = parseInt(document.getElementById('stt').value);
        let gaMeGoc = parseInt(document.getElementById('ga_me_goc').value);
        let gaConGoc = parseInt(document.getElementById('ga_con_goc').value);
        let tpGaCon = parseInt(document.getElementById('tp_ga_con').value);
        let tpGaMe = parseInt(document.getElementById('tp_ga_me').value);

        let tong = 0;

        // Công thức tính tổng dựa trên so sánh tâm điểm
        if (tpGaCon > tpGaMe) {
            // Lấy STT + TP Con + TP Mẹ + Gà Con (gốc)
            tong = stt + tpGaCon + tpGaMe + gaConGoc;
        } else if (tpGaCon < tpGaMe) {
            // Lấy STT + TP Con + TP Mẹ + Gà Mẹ (gốc)
            tong = stt + tpGaCon + tpGaMe + gaMeGoc;
        } else {
            tong = stt + tpGaCon + tpGaMe; // Trường hợp hòa
        }

        // Kiểm tra Chẵn/Lẻ
        let ketQuaText = "";
        if (tong % 2 === 0) {
            ketQuaText = "KẾT QUẢ: GÀ CON (Chẵn)";
        } else {
            ketQuaText = "KẾT QUẢ: GÀ MẸ (Lẻ)";
        }

        const resBox = document.getElementById('result-box');
        resBox.innerText = ketQuaText;
        resBox.style.color = "#d9534f"; // Đổi màu để làm nổi bật kết quả
    }
</script>

</body>
</html>
