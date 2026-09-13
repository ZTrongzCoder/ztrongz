<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tool Lọc Tài Khoản AOV Pro</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-gray-100 min-h-screen p-4 md:p-8">
    <div class="max-w-7xl mx-auto space-y-6">
        
        <!-- Header -->
        <header class="bg-gray-800 border border-gray-700 rounded-xl p-6 shadow-xl">
            <h1 class="text-2xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-purple-500">
                🚀 Hệ Thống Lọc Tài Khoản Nâng Cao
            </h1>
            <p class="text-gray-400 text-sm mt-1">Hỗ trợ lọc theo chỉ số, bộ sưu tập, trạng thái bảo mật và từ khóa tùy chỉnh.</p>
        </header>

        <!-- Nhập liệu -->
        <div class="bg-gray-800 border border-gray-700 rounded-xl p-6 shadow-xl grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="md:col-span-2 flex flex-col">
                <label class="font-semibold text-sm mb-2 text-blue-400">Dán danh sách tài khoản (Acc List):</label>
                <textarea id="rawAccs" rows="6" class="w-full bg-gray-900 border border-gray-700 rounded-lg p-3 text-sm focus:outline-none focus:border-blue-500 font-mono" placeholder="user:pass | Name: ... | Tướng: 97 | Skin: 184 | ..."></textarea>
            </div>
            <div class="flex flex-col justify-between">
                <div>
                    <label class="font-semibold text-sm mb-2 text-blue-400 block">Hoặc tải file lên (.txt):</label>
                    <input type="file" id="fileInput" accept=".txt" class="w-full text-sm text-gray-400 file:mr-4 file:py-2 file:px-4 file:rounded-lg file:border-0 file:text-sm file:font-semibold file:bg-blue-600 file:text-white hover:file:bg-blue-700 cursor-pointer">
                </div>
                <div class="mt-4">
                    <button onclick="processFiltering()" class="w-full bg-gradient-to-r from-blue-600 to-indigo-600 hover:from-blue-700 hover:to-indigo-700 text-white font-bold py-3 px-6 rounded-lg shadow-lg transition-all duration-200">
                        ⚡ BẮT ĐẦU LỌC
                    </button>
                </div>
            </div>
        </div>

        <!-- Tùy chọn lọc trùng -->
        <div class="bg-gray-800 border border-gray-700 rounded-xl p-4 shadow-xl flex flex-wrap gap-6 items-center text-sm">
            <span class="font-semibold text-purple-400">Tùy chọn xử lý trùng:</span>
            <label class="flex items-center space-x-2 cursor-pointer">
                <input type="checkbox" id="dupExact" checked class="rounded bg-gray-900 border-gray-700 text-blue-600 focus:ring-blue-500">
                <span>Bỏ trùng dòng y hệt</span>
            </label>
            <label class="flex items-center space-x-2 cursor-pointer">
                <input type="checkbox" id="dupUser" class="rounded bg-gray-900 border-gray-700 text-blue-600 focus:ring-blue-500">
                <span>Bỏ trùng theo username</span>
            </label>
            <label class="flex items-center space-x-2 cursor-pointer">
                <input type="checkbox" id="dupTrim" checked class="rounded bg-gray-900 border-gray-700 text-blue-600 focus:ring-blue-500">
                <span>Bỏ khác biệt khoảng trắng/case</span>
            </label>
        </div>

        <!-- Bộ lọc thông số & Chỉ số -->
        <div class="bg-gray-800 border border-gray-700 rounded-xl p-6 shadow-xl space-y-6">
            <h2 class="text-lg font-bold text-blue-400 border-b border-gray-700 pb-2">📊 Chỉ số cơ bản (≥)</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_tuong" class="filter-chk"><span>Tướng (≥)</span></label>
                    <input type="number" id="val_tuong" value="0" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_skin" class="filter-chk"><span>Skin (≥)</span></label>
                    <input type="number" id="val_skin" value="0" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_level" class="filter-chk"><span>Level (≥)</span></label>
                    <input type="number" id="val_level" value="0" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_qh" class="filter-chk"><span>Quân Huy (≥)</span></label>
                    <input type="number" id="val_qh" value="0" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
            </div>

            <h2 class="text-lg font-bold text-blue-400 border-b border-gray-700 pb-2 pt-2">💎 Bộ sưu tập (≥) & Chứa Skin</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_ss" class="filter-chk"><span>SS (≥)</span></label>
                    <input type="number" id="val_ss" value="0" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_sss" class="filter-chk"><span>SSS (≥)</span></label>
                    <input type="number" id="val_sss" value="0" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_anime" class="filter-chk"><span>Anime (≥)</span></label>
                    <input type="number" id="val_anime" value="0" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_other" class="filter-chk"><span>Other (≥)</span></label>
                    <input type="number" id="val_other" value="0" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_search_skin" class="filter-chk"><span>Tên Skin chứa (phẩy cách nhau)</span></label>
                    <input type="text" id="val_search_skin" placeholder="Ví dụ: Thứ Nguyên Vệ Thần, Hayate..." class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_name" class="filter-chk"><span>Tên Nhân Vật (NAME chứa)</span></label>
                    <input type="text" id="val_name" placeholder="Ví dụ: Tool1S" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                </div>
            </div>

            <h2 class="text-lg font-bold text-blue-400 border-b border-gray-700 pb-2 pt-2">🔒 Trạng thái & Bảo mật</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_band" class="filter-chk"><span>BAN / Trạng thái</span></label>
                    <select id="val_band" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                        <option value="No">Không bị Ban (No)</option>
                        <option value="Yes">Bị Ban (Yes)</option>
                    </select>
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_sdt" class="filter-chk"><span>SĐT</span></label>
                    <select id="val_sdt" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                        <option value="No">Không có SĐT (No)</option>
                        <option value="Yes">Có SĐT (Yes)</option>
                    </select>
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_email" class="filter-chk"><span>Email</span></label>
                    <select id="val_email" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                        <option value="No">Không có Email (No)</option>
                        <option value="Yes">Có Email (Yes)</option>
                    </select>
                </div>
                <div>
                    <label class="flex items-center space-x-2 text-sm mb-1"><input type="checkbox" id="chk_authen" class="filter-chk"><span>Authen</span></label>
                    <select id="val_authen" class="w-full bg-gray-900 border border-gray-700 rounded p-2 text-sm">
                        <option value="No">No</option>
                        <option value="Yes">Yes</option>
                    </select>
                </div>
            </div>
        </div>

        <!-- Kết quả -->
        <div class="bg-gray-800 border border-gray-700 rounded-xl p-6 shadow-xl space-y-4">
            <div class="flex justify-between items-center flex-wrap gap-4">
                <h2 class="text-lg font-bold text-green-400">📌 Kết quả lọc (<span id="resultCount">0</span> tài khoản)</h2>
                <div class="space-x-2">
                    <button onclick="downloadResult()" class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-lg text-sm font-semibold transition-all">📥 Tải File Kết Quả</button>
                </div>
            </div>
            <textarea id="resultOutput" rows="8" readonly class="w-full bg-gray-900 border border-gray-700 rounded-lg p-3 text-sm font-mono text-green-300" placeholder="Kết quả sẽ hiển thị ở đây..."></textarea>
        </div>

    </div>

    <script>
        // Tải file trực tiếp vào textarea
        document.getElementById('fileInput').addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (!file) return;
            const reader = new FileReader();
            reader.onload = function(evt) {
                document.getElementById('rawAccs').value = evt.target.result;
            };
            reader.readAsText(file);
        });

        // Hàm trích xuất giá trị số học hoặc chuỗi từ dòng log
        function extractField(line, fieldName) {
            const regex = new RegExp(`${fieldName}\\s*[:=]\\s*([^|]+)`, 'i');
            const match = line.match(regex);
            return match ? match[1].trim() : null;
        }

        function processFiltering() {
            const rawText = document.getElementById('rawAccs').value;
            const lines = rawText.split('\n');
            
            // Lấy trạng thái check các điều kiện
            const useTuong = document.getElementById('chk_tuong').checked;
            const minTuong = parseInt(document.getElementById('val_tuong').value) || 0;

            const useSkin = document.getElementById('chk_skin').checked;
            const minSkin = parseInt(document.getElementById('val_skin').value) || 0;

            const useLevel = document.getElementById('chk_level').checked;
            const minLevel = parseInt(document.getElementById('val_level').value) || 0;

            const useQh = document.getElementById('chk_qh').checked;
            const minQh = parseInt(document.getElementById('val_qh').value) || 0;

            const useSs = document.getElementById('chk_ss').checked;
            const minSs = parseInt(document.getElementById('val_ss').value) || 0;

            const useSss = document.getElementById('chk_sss').checked;
            const minSss = parseInt(document.getElementById('val_sss').value) || 0;

            const useAnime = document.getElementById('chk_anime').checked;
            const minAnime = parseInt(document.getElementById('val_anime').value) || 0;

            const useOther = document.getElementById('chk_other').checked;
            const minOther = parseInt(document.getElementById('val_other').value) || 0;

            const useSearchSkin = document.getElementById('chk_search_skin').checked;
            const searchSkinVal = document.getElementById('val_search_skin').value.toLowerCase();

            const useName = document.getElementById('chk_name').checked;
            const searchNameVal = document.getElementById('val_name').value.toLowerCase();

            const useBand = document.getElementById('chk_band').checked;
            const valBand = document.getElementById('val_band').value;

            const useSdt = document.getElementById('chk_sdt').checked;
            const valSdt = document.getElementById('val_sdt').value;

            const useEmail = document.getElementById('chk_email').checked;
            const valEmail = document.getElementById('val_email').value;

            const useAuthen = document.getElementById('chk_authen').checked;
            const valAuthen = document.getElementById('val_authen').value;

            // Xử lý tùy chọn trùng
            const dupExact = document.getElementById('dupExact').checked;
            const dupUser = document.getElementById('dupUser').checked;
            const dupTrim = document.getElementById('dupTrim').checked;

            let filtered = [];
            let seen = new Set();

            for (let line of lines) {
                let cleanLine = line.trim();
                if (!cleanLine) continue;

                let compareLine = dupTrim ? cleanLine.toLowerCase() : cleanLine;
                
                // Trích xuất username nếu cần lọc trùng theo user
                let parts = cleanLine.split('|');
                let firstPart = parts[0].trim();
                let username = firstPart.includes(':') ? firstPart.split(':')[0].trim() : firstPart;

                if (dupExact) {
                    if (seen.has(compareLine)) continue;
                    seen.add(compareLine);
                } else if (dupUser) {
                    if (seen.has(username)) continue;
                    seen.add(username);
                }

                // Kiểm tra điều kiện số lượng
                if (useTuong) {
                    let val = parseInt(extractField(cleanLine, 'Tướng')) || 0;
                    if (val < minTuong) continue;
                }
                if (useSkin) {
                    let val = parseInt(extractField(cleanLine, 'Skin')) || 0;
                    if (val < minSkin) continue;
                }
                if (useLevel) {
                    let val = parseInt(extractField(cleanLine, 'Level')) || 0;
                    if (val < minLevel) continue;
                }
                if (useQh) {
                    let val = parseInt(extractField(cleanLine, 'Quân Huy')) || 0;
                    if (val < minQh) continue;
                }
                if (useSs) {
                    let val = parseInt(extractField(cleanLine, 'SS')) || 0;
                    if (val < minSs) continue;
                }
                if (useSss) {
                    let val = parseInt(extractField(cleanLine, 'SSS')) || 0;
                    if (val < minSss) continue;
                }
                if (useAnime) {
                    let val = parseInt(extractField(cleanLine, 'Anime')) || 0;
                    if (val < minAnime) continue;
                }
                if (useOther) {
                    let val = parseInt(extractField(cleanLine, 'Other')) || 0;
                    if (val < minOther) continue;
                }

                // Kiểm tra chứa Skin yêu cầu
                if (useSearchSkin && searchSkinVal) {
                    let skinsKeyword = searchSkinVal.split(',').map(s => s.trim()).filter(Boolean);
                    let matched = skinsKeyword.every(kw => cleanLine.toLowerCase().includes(kw));
                    if (!matched) continue;
                }

                // Kiểm tra tên nhân vật
                if (useName && searchNameVal) {
                    let nameVal = (extractField(cleanLine, 'Name') || '').toLowerCase();
                    if (!nameVal.includes(searchNameVal)) continue;
                }

                // Kiểm tra trạng thái Ban
                if (useBand) {
                    let banVal = extractField(cleanLine, 'Ban');
                    if (valBand === 'No' && banVal && !banVal.toLowerCase().includes('no')) continue;
                    if (valBand === 'Yes' && (!banVal || banVal.toLowerCase().includes('no'))) continue;
                }

                // Kiểm tra SĐT
                if (useSdt) {
                    let sdtVal = extractField(cleanLine, 'SĐT');
                    if (valSdt === 'No' && sdtVal && !sdtVal.toLowerCase().includes('no')) continue;
                    if (valSdt === 'Yes' && (!sdtVal || sdtVal.toLowerCase().includes('no'))) continue;
                }

                // Kiểm tra Email
                if (useEmail) {
                    let emailVal = extractField(cleanLine, 'Email');
                    if (valEmail === 'No' && emailVal && !emailVal.toLowerCase().includes('no')) continue;
                    if (valEmail === 'Yes' && (!emailVal || emailVal.toLowerCase().includes('no'))) continue;
                }

                // Kiểm tra Authen
                if (useAuthen) {
                    let authenVal = extractField(cleanLine, 'Authen');
                    if (valAuthen === 'No' && authenVal && !authenVal.toLowerCase().includes('no')) continue;
                    if (valAuthen === 'Yes' && (!authenVal || authenVal.toLowerCase().includes('no'))) continue;
                }

                filtered.push(cleanLine);
            }

            document.getElementById('resultCount').innerText = filtered.length;
            document.getElementById('resultOutput').value = filtered.join('\n');
        }

        function downloadResult() {
            const text = document.getElementById('resultOutput').value;
            if (!text) {
                alert("Không có dữ liệu để tải xuống!");
                return;
            }
            const blob = new Blob([text], { type: 'text/plain;charset=utf-8' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'ket_qua_loc.txt';
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
        }
    </script>
</body>
</html>
