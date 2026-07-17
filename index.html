<!DOCTYPE html>
<html lang="th" class="h-full bg-slate-50">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ระบบประเมินหลักสูตร - โรงเรียนรัฐประชาวิทยาคาร</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Sarabun & Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Chart.js for Admin Analytics -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <!-- SheetJS for Premium Client-Side Excel Generation -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Sarabun', 'Inter', 'sans-serif'],
                    },
                    colors: {
                        primary: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#3b82f6',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            800: '#1e40af',
                            900: '#1e3a8a',
                            950: '#172554'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .tab-transition {
            transition: all 0.3s ease-in-out;
        }
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
    </style>
</head>
<body class="h-full font-sans antialiased text-slate-800 flex flex-col">

    <div class="flex h-screen overflow-hidden bg-slate-100 w-full">
        <!-- Sidebar Navigation -->
        <aside id="sidebar" class="fixed inset-y-0 left-0 z-50 flex flex-col w-72 bg-primary-950 text-white transform -translate-x-full md:translate-x-0 md:static transition-transform duration-300 ease-in-out">
            <!-- Sidebar Header -->
            <div class="flex items-center justify-between h-20 px-6 bg-slate-900 border-b border-primary-900">
                <div class="flex items-center space-x-3">
                    <div class="p-2.5 bg-primary-800 rounded-lg text-amber-400">
                        <i class="fa-solid fa-school text-xl"></i>
                    </div>
                    <div>
                        <h2 class="font-bold text-sm leading-tight">โรงเรียนรัฐประชาฯ</h2>
                        <p class="text-xs text-primary-300">ระบบประเมินหลักสูตร</p>
                    </div>
                </div>
                <button onclick="toggleSidebar()" class="md:hidden text-white hover:text-slate-200">
                    <i class="fa-solid fa-xmark text-xl"></i>
                </button>
            </div>

            <!-- School Context Meta Info -->
            <div class="px-6 py-4 bg-primary-900/40 border-b border-primary-900/60 text-xs text-primary-200">
                <p class="font-semibold"><i class="fa-solid fa-circle-info mr-1 text-amber-400"></i> สังกัดหน่วยงาน</p>
                <p class="mt-1 opacity-80">สพป.ร้อยเอ็ด เขต 1</p>
                <p class="opacity-80">สำนักงานคณะกรรมการการศึกษาขั้นพื้นฐาน</p>
            </div>

            <!-- Navigation Links -->
            <nav class="flex-1 px-4 py-6 space-y-2 overflow-y-auto">
                <button onclick="switchTab('form')" id="nav-form" class="w-full flex items-center px-4 py-3 text-sm font-medium rounded-xl transition-all duration-200 bg-primary-800 text-white shadow-lg shadow-primary-950/40">
                    <i class="fa-solid fa-file-signature mr-3.5 text-lg"></i>
                    <span>📝 กรอกแบบประเมินหลักสูตร</span>
                </button>
                <button onclick="switchTab('admin')" id="nav-admin" class="w-full flex items-center px-4 py-3 text-sm font-medium rounded-xl transition-all duration-200 text-primary-100 hover:bg-primary-800/50 hover:text-white">
                    <i class="fa-solid fa-lock mr-3.5 text-lg"></i>
                    <span>📊 แผงควบคุมระบบ (Admin)</span>
                </button>
            </nav>

            <!-- Sidebar Footer -->
            <div class="p-5 border-t border-primary-900 bg-slate-900 text-center text-xs text-primary-300">
                <p>เวอร์ชันระบบ 4.0 (Premium Dual-Year)</p>
                <p class="mt-1 opacity-60">อิงเอกสารหลักสูตร ปี 2568</p>
            </div>
        </aside>

        <!-- Main Content Area -->
        <main class="flex-1 flex flex-col overflow-y-auto relative focus:outline-none bg-slate-50">
            <!-- Top Header Navbar -->
            <header class="flex items-center justify-between h-16 px-6 bg-white border-b border-slate-200 shadow-sm shrink-0">
                <div class="flex items-center space-x-3">
                    <button onclick="toggleSidebar()" class="p-2 text-slate-500 rounded-lg hover:bg-slate-100 md:hidden">
                        <i class="fa-solid fa-bars text-lg"></i>
                    </button>
                    <h1 id="page-title-header" class="text-lg font-bold text-slate-800">กรอกแบบประเมินผลการใช้หลักสูตร</h1>
                </div>
                <!-- Document Name Indicator Badge (Verbatim reference to original source) -->
                <div class="hidden sm:flex items-center bg-blue-50 border border-blue-200 text-primary-900 px-3.5 py-1.5 rounded-full text-xs font-semibold">
                    <i class="fa-solid fa-file-word text-blue-600 mr-2"></i>
                    อ้างอิงเอกสาร: ตัวอย่าง แบบประเมินหลักสูตร_2.docx
                </div>
            </header>

            <div class="flex-1 p-4 sm:p-6 max-w-7xl w-full mx-auto space-y-6">

                <!-- SCREEN 1: EVALUATION FORM -->
                <section id="panel-form" class="space-y-6">
                    <!-- Main Header Banner -->
                    <div class="bg-gradient-to-r from-primary-950 via-primary-900 to-primary-800 rounded-2xl p-6 sm:p-8 text-white shadow-xl relative overflow-hidden">
                        <div class="absolute right-0 bottom-0 opacity-10 transform translate-x-12 translate-y-12">
                            <i class="fa-solid fa-graduation-cap text-[200px]"></i>
                        </div>
                        <div class="relative z-10 max-w-3xl">
                            <span class="bg-amber-400 text-primary-950 px-3 py-1 rounded-full text-xs font-bold uppercase tracking-wider">ส่วนประเมินการศึกษา</span>
                            <h2 class="text-xl sm:text-2xl font-extrabold mt-3">แบบประเมินผลการใช้หลักสูตรสถานศึกษา</h2>
                            <p class="text-primary-100 mt-2 text-xs sm:text-sm leading-relaxed opacity-90">
                                ตามหลักสูตรแกนกลางการศึกษาขั้นพื้นฐาน พุทธศักราช 2551 (ฉบับปรับปรุง พุทธศักราช 2560)<br>
                                โรงเรียนรัฐประชาวิทยาคาร สำนักงานเขตพื้นที่การศึกษาประถมศึกษาร้อยเอ็ด เขต 1
                            </p>
                        </div>
                    </div>

                    <!-- Criteria Description Card -->
                    <div class="bg-amber-50 border-l-4 border-amber-500 p-4 rounded-r-xl shadow-sm">
                        <div class="flex">
                            <div class="flex-shrink-0 text-amber-500 text-lg">
                                <i class="fa-solid fa-circle-question"></i>
                            </div>
                            <div class="ml-3">
                                <h3 class="text-sm font-bold text-amber-800">คำชี้แจงในการให้คะแนนประเมิน (เกณฑ์ประเมินระดับคุณภาพ 4 ระดับ)</h3>
                                <div class="mt-2 text-xs text-amber-700 space-y-1">
                                    <p><strong>ระดับ 4 (มากที่สุด / สอดคล้องถูกต้องมากที่สุด):</strong> มีการปฏิบัติในระดับมากที่สุด หรือมีความสอดคล้องถูกต้องมากที่สุด หรือปฏิบัติ 7-8 กลุ่มสาระการเรียนรู้</p>
                                    <p><strong>ระดับ 3 (มาก / สอดคล้องถูกต้องมาก):</strong> มีการปฏิบัติในระดับมาก หรือมีความสอดคล้องถูกต้องมาก หรือปฏิบัติ 5-6 กลุ่มสาระการเรียนรู้</p>
                                    <p><strong>ระดับ 2 (ปานกลาง / สอดคล้องถูกต้องปานกลาง):</strong> มีการปฏิบัติในระดับปานกลาง หรือมีความสอดคล้องถูกต้องปานกลาง หรือปฏิบัติ 3-4 กลุ่มสาระการเรียนรู้</p>
                                    <p><strong>ระดับ 1 (น้อย / สอดคล้องถูกต้องน้อย):</strong> มีการปฏิบัติในระดับน้อย หรือมีความสอดคล้องถูกต้องน้อย หรือปฏิบัติน้อยกว่า 3 กลุ่มสาระการเรียนรู้</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- STEPPER NAVIGATION BUTTONS -->
                    <div class="flex flex-wrap gap-2 border-b border-slate-200 pb-2">
                        <button onclick="switchFormStep(1)" id="step-btn-1" class="px-4 py-2.5 text-xs sm:text-sm font-bold rounded-lg bg-primary-600 text-white shadow-md transition-all">1. ข้อมูลทั่วไปผู้ประเมิน</button>
                        <button onclick="switchFormStep(2)" id="step-btn-2" class="px-4 py-2.5 text-xs sm:text-sm font-bold rounded-lg bg-white text-slate-600 border border-slate-200 hover:bg-slate-50 transition-all">2. ตอนที่ 1: องค์ประกอบหลักสูตร</button>
                        <button onclick="switchFormStep(3)" id="step-btn-3" class="px-4 py-2.5 text-xs sm:text-sm font-bold rounded-lg bg-white text-slate-600 border border-slate-200 hover:bg-slate-50 transition-all">3. ตอนที่ 2: การนำสู่การเรียนรู้</button>
                        <button onclick="switchFormStep(4)" id="step-btn-4" class="px-4 py-2.5 text-xs sm:text-sm font-bold rounded-lg bg-white text-slate-600 border border-slate-200 hover:bg-slate-50 transition-all">4. ข้อเสนอแนะ & บันทึก</button>
                    </div>

                    <!-- FORM STARTS HERE -->
                    <form id="evaluation-form" onsubmit="handleFormSubmit(event)" class="space-y-6">
                        
                        <!-- STEP 1: GENERAL INFO & SUBJECT DETAILS (Separated by Academic Year) -->
                        <div id="step-container-1" class="bg-white rounded-2xl p-6 shadow-sm border border-slate-100 space-y-6">
                            <div class="border-b border-slate-100 pb-4">
                                <h3 class="text-base sm:text-lg font-bold text-slate-800"><i class="fa-solid fa-user-tie text-primary-600 mr-2"></i> ข้อมูลทั่วไปของผู้ประเมิน</h3>
                                <p class="text-xs text-slate-500 mt-1">กรุณากรอกรายละเอียดเพื่อเก็บสถิติอย่างถูกต้อง แยกจำแนกตามรายปีการศึกษาและสาระเรียนรู้</p>
                            </div>
                            
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div>
                                    <label class="block text-sm font-semibold text-slate-700 mb-2">ปีการศึกษาที่ต้องการประเมิน <span class="text-red-500">*</span></label>
                                    <select id="evaluator-year" required class="w-full rounded-xl border border-slate-200 px-4 py-2.5 text-sm font-bold focus:outline-none focus:ring-2 focus:ring-primary-500 bg-amber-50 border-amber-200 text-amber-950">
                                        <option value="2568" selected>ปีการศึกษา 2568</option>
                                        <option value="2569">ปีการศึกษา 2569</option>
                                        <option value="2570">ปีการศึกษา 2570</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-sm font-semibold text-slate-700 mb-2">ชื่อ-นามสกุล ครูผู้สอน / ผู้ประเมิน <span class="text-red-500">*</span></label>
                                    <input type="text" id="evaluator-name" required class="w-full rounded-xl border border-slate-200 px-4 py-2.5 text-sm focus:outline-none focus:ring-2 focus:ring-primary-500 bg-slate-50 hover:bg-slate-100/50 transition-all" placeholder="ระบุ ชื่อ และนามสกุล">
                                </div>
                                <div>
                                    <label class="block text-sm font-semibold text-slate-700 mb-2">ตำแหน่งทางการศึกษา <span class="text-red-500">*</span></label>
                                    <select id="evaluator-position" required class="w-full rounded-xl border border-slate-200 px-4 py-2.5 text-sm focus:outline-none focus:ring-2 focus:ring-primary-500 bg-slate-50">
                                        <option value="ครู">ครู</option>
                                        <option value="ผู้อำนวยการโรงเรียน">ผู้อำนวยการโรงเรียน</option>
                                        <option value="รองผู้อำนวยการโรงเรียน">รองผู้อำนวยการโรงเรียน</option>
                                        <option value="บุคลากรทางการศึกษาอื่นๆ">บุคลากรทางการศึกษาอื่นๆ</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-sm font-semibold text-slate-700 mb-2">กลุ่มสาระการเรียนรู้ที่สังกัดหลัก <span class="text-red-500">*</span></label>
                                    <select id="evaluator-department" required class="w-full rounded-xl border border-slate-200 px-4 py-2.5 text-sm focus:outline-none focus:ring-2 focus:ring-primary-500 bg-slate-50">
                                        <option value="วิทยาศาสตร์และเทคโนโลยี">วิทยาศาสตร์และเทคโนโลยี</option>
                                        <option value="คณิตศาสตร์">คณิตศาสตร์</option>
                                        <option value="ภาษาไทย">ภาษาไทย</option>
                                        <option value="ภาษาต่างประเทศ">ภาษาต่างประเทศ</option>
                                        <option value="สังคมศึกษา ศาสนา และวัฒนธรรม">สังคมศึกษา ศาสนา และวัฒนธรรม</option>
                                        <option value="สุขศึกษาและพลศึกษา">สุขศึกษาและพลศึกษา</option>
                                        <option value="ศิลปะ">ศิลปะ</option>
                                        <option value="การงานอาชีพ">การงานอาชีพ</option>
                                    </select>
                                </div>
                            </div>

                            <!-- Subject Detail Grids (Up to 3 subjects verbatim from source document) -->
                            <div class="mt-8 pt-6 border-t border-slate-150">
                                <h4 class="text-sm font-bold text-slate-800 mb-4"><i class="fa-solid fa-book-bookmark text-amber-500 mr-2"></i> รายละเอียดวิชา/กลุ่มงานสอนที่รับผิดชอบ (ระบุสูงสุด 3 รายวิชา)</h4>
                                
                                <div class="space-y-4">
                                    <!-- Subject Row 1 -->
                                    <div class="p-4 bg-slate-50/50 rounded-xl border border-slate-150 grid grid-cols-1 md:grid-cols-3 gap-4">
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">รหัสวิชา (วิชาที่ 1) <span class="text-red-500">*</span></label>
                                            <input type="text" id="subj1-code" required class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="เช่น ว15101">
                                        </div>
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">ชื่อรายวิชา (วิชาที่ 1) <span class="text-red-500">*</span></label>
                                            <input type="text" id="subj1-name" required class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="เช่น วิทยาศาสตร์และเทคโนโลยี">
                                        </div>
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">ระดับชั้นเรียน (วิชาที่ 1) <span class="text-red-500">*</span></label>
                                            <input type="text" id="subj1-grade" required class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="เช่น ป.5">
                                        </div>
                                    </div>

                                    <!-- Subject Row 2 -->
                                    <div class="p-4 bg-slate-50/50 rounded-xl border border-slate-150 grid grid-cols-1 md:grid-cols-3 gap-4">
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">รหัสวิชา (วิชาที่ 2)</label>
                                            <input type="text" id="subj2-code" class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="ปล่อยว่างหากไม่มี">
                                        </div>
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">ชื่อรายวิชา (วิชาที่ 2)</label>
                                            <input type="text" id="subj2-name" class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="ปล่อยว่างหากไม่มี">
                                        </div>
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">ระดับชั้นเรียน (วิชาที่ 2)</label>
                                            <input type="text" id="subj2-grade" class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="ปล่อยว่างหากไม่มี">
                                        </div>
                                    </div>

                                    <!-- Subject Row 3 -->
                                    <div class="p-4 bg-slate-50/50 rounded-xl border border-slate-150 grid grid-cols-1 md:grid-cols-3 gap-4">
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">รหัสวิชา (วิชาที่ 3)</label>
                                            <input type="text" id="subj3-code" class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="ปล่อยว่างหากไม่มี">
                                        </div>
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">ชื่อรายวิชา (วิชาที่ 3)</label>
                                            <input type="text" id="subj3-name" class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="ปล่อยว่างหากไม่มี">
                                        </div>
                                        <div>
                                            <label class="block text-xs font-semibold text-slate-600 mb-1">ระดับชั้นเรียน (วิชาที่ 3)</label>
                                            <input type="text" id="subj3-grade" class="w-full rounded-lg border border-slate-200 px-3 py-2 text-xs bg-white focus:outline-none" placeholder="ปล่อยว่างหากไม่มี">
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="flex justify-end pt-4">
                                <button type="button" onclick="switchFormStep(2)" class="px-6 py-3 rounded-xl bg-primary-600 text-white font-bold text-sm hover:bg-primary-700 transition-all shadow-md">
                                    ถัดไป: ตอนที่ 1 <i class="fa-solid fa-arrow-right ml-1"></i>
                                </button>
                            </div>
                        </div>

                        <!-- STEP 2: PART 1 QUESTIONS -->
                        <div id="step-container-2" class="hidden bg-white rounded-2xl p-6 shadow-sm border border-slate-100 space-y-6">
                            <div class="border-b border-slate-100 pb-4">
                                <h3 class="text-base sm:text-lg font-bold text-slate-800"><i class="fa-solid fa-book-open text-primary-600 mr-2"></i> ตอนที่ 1: องค์ประกอบของหลักสูตรสถานศึกษา</h3>
                                <p class="text-xs text-slate-500 mt-1">พิจารณาความถูกต้องตามองค์ประกอบโครงสร้าง สาระความรู้ ท้องถิ่น และหลักสูตรสถานศึกษาให้ถูกต้องตามไฟล์อ้างอิง</p>
                            </div>

                            <div id="part1-questions-render" class="space-y-6">
                                <!-- Generated Dynamically by Javascript -->
                            </div>

                            <div class="pt-6 border-t border-slate-100">
                                <label class="block text-sm font-semibold text-slate-700 mb-2">ข้อเสนอแนะ ปรับปรุง/แก้ไข ตอนที่ 1</label>
                                <textarea id="suggestions-part1" rows="3" class="w-full rounded-xl border border-slate-200 px-4 py-2.5 text-sm focus:outline-none bg-slate-50 focus:ring-2 focus:ring-primary-500" placeholder="โปรดระบุความคิดเห็นในการพัฒนาส่วนนำ โครงสร้างหลักสูตร หรือคำอธิบายรายวิชาเพิ่มเติม..."></textarea>
                            </div>

                            <div class="flex justify-between pt-6 border-t border-slate-100">
                                <button type="button" onclick="switchFormStep(1)" class="px-5 py-2.5 rounded-xl border border-slate-200 text-slate-600 font-bold text-sm hover:bg-slate-100 transition-all">
                                    <i class="fa-solid fa-arrow-left mr-1"></i> ย้อนกลับ
                                </button>
                                <button type="button" onclick="switchFormStep(3)" class="px-5 py-2.5 rounded-xl bg-primary-600 text-white font-bold text-sm hover:bg-primary-700 transition-all shadow-md">
                                    ถัดไป: ตอนที่ 2 <i class="fa-solid fa-arrow-right ml-1"></i>
                                </button>
                            </div>
                        </div>

                        <!-- STEP 3: PART 2 QUESTIONS -->
                        <div id="step-container-3" class="hidden bg-white rounded-2xl p-6 shadow-sm border border-slate-100 space-y-6">
                            <div class="border-b border-slate-100 pb-4">
                                <h3 class="text-base sm:text-lg font-bold text-slate-800"><i class="fa-solid fa-chalkboard-user text-primary-600 mr-2"></i> ตอนที่ 2: การนำหลักสูตรสถานศึกษาสู่การจัดการเรียนรู้ (หลักสูตรระดับชั้นเรียน)</h3>
                                <p class="text-xs text-slate-500 mt-1">ประเมินโครงสร้างวิชา แผนการสอน Active Learning และแนวทางบูรณาการนวัตกรรมอย่างยั่งยืนสอดคล้องตามต้นฉบับ</p>
                            </div>

                            <div id="part2-questions-render" class="space-y-6">
                                <!-- Generated Dynamically by Javascript -->
                            </div>

                            <div class="pt-6 border-t border-slate-100">
                                <label class="block text-sm font-semibold text-slate-700 mb-2">ข้อเสนอแนะ ปรับปรุง/แก้ไข ตอนที่ 2</label>
                                <textarea id="suggestions-part2" rows="3" class="w-full rounded-xl border border-slate-200 px-4 py-2.5 text-sm focus:outline-none bg-slate-50 focus:ring-2 focus:ring-primary-500" placeholder="ระบุความคิดเห็นเพื่อพัฒนาหน่วยการเรียนรู้ สื่อเทคโนโลยี แผน Active Learning หรือกระบวนการนิเทศหลักสูตร..."></textarea>
                            </div>

                            <div class="flex justify-between pt-6 border-t border-slate-100">
                                <button type="button" onclick="switchFormStep(2)" class="px-5 py-2.5 rounded-xl border border-slate-200 text-slate-600 font-bold text-sm hover:bg-slate-100 transition-all">
                                    <i class="fa-solid fa-arrow-left mr-1"></i> ย้อนกลับ
                                </button>
                                <button type="button" onclick="switchFormStep(4)" class="px-5 py-2.5 rounded-xl bg-primary-600 text-white font-bold text-sm hover:bg-primary-700 transition-all shadow-md">
                                    ถัดไป: สรุป & ยืนยัน <i class="fa-solid fa-arrow-right ml-1"></i>
                                </button>
                            </div>
                        </div>

                        <!-- STEP 4: SUGGESTIONS & CONFIRM SUBMIT -->
                        <div id="step-container-4" class="hidden bg-white rounded-2xl p-6 shadow-sm border border-slate-100 space-y-6">
                            <div class="border-b border-slate-100 pb-4">
                                <h3 class="text-base sm:text-lg font-bold text-slate-800"><i class="fa-solid fa-lightbulb text-primary-600 mr-2"></i> ข้อเสนอแนะอื่นๆ เพื่อนำไปพัฒนาหลักสูตรสถานศึกษา ปีการศึกษา 2569</h3>
                                <p class="text-xs text-slate-500 mt-1">ส่วนบันทึกข้อมูลและสรุปความคิดเห็นสำหรับการพัฒนาหลักสูตรในภาพรวม</p>
                            </div>

                            <div>
                                <label class="block text-sm font-semibold text-slate-700 mb-2">ข้อเสนอแนะเพิ่มเติมในภาพรวม</label>
                                <textarea id="suggestions-general" rows="6" class="w-full rounded-xl border border-slate-200 px-4 py-2.5 text-sm focus:outline-none bg-slate-50 focus:ring-2 focus:ring-primary-500" placeholder="ระบุความต้องการการสนับสนุนเชิงทรัพยากร ปัจจัย หรือข้อคิดเห็นเพิ่มเติมที่โรงเรียนสามารถนำไปใช้วางแผนปีการศึกษาถัดไปได้..."></textarea>
                            </div>

                            <div class="flex flex-col sm:flex-row gap-3 justify-between pt-6 border-t border-slate-100">
                                <button type="button" onclick="switchFormStep(3)" class="px-5 py-2.5 rounded-xl border border-slate-200 text-slate-600 font-bold text-sm hover:bg-slate-100 transition-all">
                                    <i class="fa-solid fa-arrow-left mr-1"></i> ย้อนกลับ
                                </button>
                                <button type="submit" class="px-8 py-3 rounded-xl bg-gradient-to-r from-emerald-600 to-teal-500 text-white font-bold text-sm hover:from-emerald-700 hover:to-teal-600 transition-all shadow-lg shadow-emerald-500/20">
                                    <i class="fa-solid fa-cloud-arrow-up mr-1"></i> ส่งแบบประเมินเข้าระบบ
                                </button>
                            </div>
                        </div>

                    </form>
                </section>

                <!-- SCREEN 2: ADMIN PANEL (LOCKED BY PASSWORD OPTION) -->
                <section id="panel-admin" class="hidden space-y-6">
                    
                    <!-- LOBBY LOGIN INTERFACE (RENDERED CONDITIONALLY) -->
                    <div id="admin-login-lobby" class="max-w-md mx-auto my-12 bg-white rounded-2xl shadow-xl border border-slate-200 overflow-hidden">
                        <div class="bg-primary-950 p-6 text-center text-white">
                            <div class="w-16 h-16 bg-primary-800/80 text-amber-400 rounded-full flex items-center justify-center mx-auto mb-3 border border-primary-700">
                                <i class="fa-solid fa-shield-halved text-2xl animate-pulse"></i>
                            </div>
                            <h3 class="font-extrabold text-base sm:text-lg">แผงควบคุมแอดมินวิชาการ</h3>
                            <p class="text-xs text-primary-300 mt-1">โรงเรียนรัฐประชาวิทยาคาร สพป.ร้อยเอ็ด เขต 1</p>
                        </div>
                        <div class="p-6 space-y-4 bg-white">
                            <p class="text-xs text-slate-500 text-center leading-relaxed">
                                เพื่อความปลอดภัยของสถิติวิเคราะห์ของโรงเรียนเฉพาะเจ้าหน้าที่วิชาการที่ได้รับอนุญาตกรุณาระบุรหัสผ่านเข้าถึงระบบ
                            </p>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1.5 uppercase font-sans">รหัสผ่านสำหรับแอดมิน (Hint: admin1234)</label>
                                <div class="relative">
                                    <input type="password" id="admin-password-input" class="w-full px-4 py-2.5 text-sm rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-primary-500 bg-slate-50" placeholder="ระบุรหัสผ่านแอดมิน">
                                    <button type="button" onclick="togglePasswordVisibility()" class="absolute right-3.5 top-3 text-slate-400 hover:text-slate-600 transition-colors">
                                        <i id="password-toggle-icon" class="fa-solid fa-eye text-xs"></i>
                                    </button>
                                </div>
                            </div>
                            <button onclick="attemptAdminLogin()" class="w-full py-2.5 bg-primary-800 hover:bg-primary-900 text-white font-bold text-xs rounded-xl transition-all shadow-md">
                                <i class="fa-solid fa-unlock-keyhole mr-1"></i> เข้าสู่ระบบแอดมิน
                            </button>
                        </div>
                    </div>

                    <!-- MAIN ADMIN CORE (LOCKED CONTENT HIDDEN BY DEFAULT) -->
                    <div id="admin-authenticated-content" class="hidden space-y-6">
                        <!-- Admin Panel Hero Block -->
                        <div class="bg-slate-900 rounded-2xl p-6 text-white shadow-xl flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
                            <div>
                                <span class="bg-primary-600 text-white px-2.5 py-0.5 rounded-md text-[10px] font-bold uppercase tracking-wider">แผงวิเคราะห์ระดับผู้ดูแล (Authorized)</span>
                                <h2 class="text-lg sm:text-xl font-bold mt-2">ศูนย์วิเคราะห์ผลหลังบ้านและประมวลข้อมูลดิบ</h2>
                                <p class="text-slate-400 text-xs mt-1">ประมวลรายงาน จัดเก็บข้อมูลดิบ สรุปค่าเฉลี่ยสถิติ และแยกแยะรายปีการศึกษา</p>
                            </div>
                            <div class="flex flex-wrap gap-2 w-full md:w-auto">
                                <button onclick="triggerExcelDownload()" class="flex-1 md:flex-none flex items-center justify-center px-4 py-2.5 bg-emerald-600 hover:bg-emerald-700 text-white font-bold text-xs rounded-xl transition-all shadow-md shadow-emerald-950/20">
                                    <i class="fa-solid fa-file-excel mr-1.5 text-sm"></i> ดาวน์โหลดรายงานพรีเมียม (Excel)
                                </button>
                                <button onclick="generateMockData()" class="flex-1 md:flex-none flex items-center justify-center px-4 py-2.5 bg-primary-600 hover:bg-primary-700 text-white font-bold text-xs rounded-xl transition-all shadow-md shadow-primary-950/20">
                                    <i class="fa-solid fa-wand-magic-sparkles mr-1.5"></i> สุ่มข้อมูลทดสอบ
                                </button>
                                <button onclick="triggerAdminLogout()" class="p-2.5 bg-red-950/40 text-red-300 hover:bg-red-900 hover:text-white rounded-xl transition-colors" title="ออกจากระบบความปลอดภัย">
                                    <i class="fa-solid fa-power-off"></i> ออกจากระบบ
                                </button>
                                <button onclick="openConfirmModal()" class="p-2.5 bg-slate-800 hover:bg-red-900 hover:text-red-200 text-slate-400 rounded-xl transition-colors" title="ล้างข้อมูลระบบ">
                                    <i class="fa-solid fa-trash-can"></i> ล้างข้อมูลทั้งหมด
                                </button>
                            </div>
                        </div>

                        <!-- Academic Year Filter Area -->
                        <div class="bg-white p-5 rounded-2xl border border-slate-100 shadow-sm flex flex-col sm:flex-row items-center justify-between gap-4">
                            <div class="flex items-center space-x-3">
                                <div class="p-2 bg-amber-50 rounded-lg text-amber-500">
                                    <i class="fa-solid fa-calendar-days text-lg"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-sm text-slate-800">ปีการศึกษาที่กรองข้อมูล</h4>
                                    <p class="text-xs text-slate-400">เลือกปีการศึกษาที่ต้องการแยกประมวลผลสถิติและฐานข้อมูลดิบ</p>
                                </div>
                            </div>
                            <div class="w-full sm:w-72">
                                <select id="admin-year-filter" onchange="handleYearFilterChange()" class="w-full rounded-xl border border-slate-200 px-4 py-2.5 text-sm font-bold bg-slate-50 focus:outline-none focus:ring-2 focus:ring-primary-500 text-primary-900">
                                    <option value="ทั้งหมด">ทั้งหมด (ทุกปีการศึกษา)</option>
                                    <option value="2568" selected>ปีการศึกษา 2568</option>
                                    <option value="2569">ปีการศึกษา 2569</option>
                                    <option value="2570">ปีการศึกษา 2570</option>
                                </select>
                            </div>
                        </div>

                        <!-- METRICS DISPLAY GRID -->
                        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                            <div class="bg-white p-5 rounded-xl border border-slate-100 shadow-sm flex items-center space-x-4">
                                <div class="p-4 bg-primary-50 text-primary-600 rounded-lg">
                                    <i class="fa-solid fa-users text-xl"></i>
                                </div>
                                <div>
                                    <p class="text-[10px] text-slate-500 font-semibold uppercase tracking-wider">ผู้ตอบประเมินสะสม</p>
                                    <p id="stat-total-count" class="text-2xl font-black text-slate-800 mt-0.5">0</p>
                                </div>
                            </div>
                            <div class="bg-white p-5 rounded-xl border border-slate-100 shadow-sm flex items-center space-x-4">
                                <div class="p-4 bg-emerald-50 text-emerald-600 rounded-lg">
                                    <i class="fa-solid fa-bookmark text-xl"></i>
                                </div>
                                <div>
                                    <p class="text-[10px] text-slate-500 font-semibold uppercase tracking-wider">คะแนนเฉลี่ยตอนที่ 1</p>
                                    <p id="stat-p1-avg" class="text-2xl font-black text-emerald-600 mt-0.5">0.00 / 4</p>
                                </div>
                            </div>
                            <div class="bg-white p-5 rounded-xl border border-slate-100 shadow-sm flex items-center space-x-4">
                                <div class="p-4 bg-teal-50 text-teal-600 rounded-lg">
                                    <i class="fa-solid fa-chalkboard text-xl"></i>
                                </div>
                                <div>
                                    <p class="text-[10px] text-slate-500 font-semibold uppercase tracking-wider">คะแนนเฉลี่ยตอนที่ 2</p>
                                    <p id="stat-p2-avg" class="text-2xl font-black text-teal-600 mt-0.5">0.00 / 4</p>
                                </div>
                            </div>
                            <div class="bg-white p-5 rounded-xl border border-slate-100 shadow-sm flex items-center space-x-4">
                                <div class="p-4 bg-purple-50 text-purple-600 rounded-lg">
                                    <i class="fa-solid fa-ranking-star text-xl"></i>
                                </div>
                                <div>
                                    <p class="text-[10px] text-slate-500 font-semibold uppercase tracking-wider">ภาพรวมคุณภาพหลักสูตร</p>
                                    <p id="stat-overall-avg" class="text-2xl font-black text-purple-600 mt-0.5">0.00 / 4</p>
                                </div>
                            </div>
                        </div>

                        <!-- CHARTS GRID -->
                        <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                            <!-- Chart 1: Role Doughnut -->
                            <div class="bg-white p-5 rounded-2xl border border-slate-100 shadow-sm space-y-4">
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800"><i class="fa-solid fa-chart-pie text-primary-500 mr-2"></i> สัดส่วนจำแนกตามตำแหน่งผู้ประเมิน</h3>
                                <div class="relative h-64 flex justify-center">
                                    <canvas id="chart-roles"></canvas>
                                </div>
                            </div>
                            <!-- Chart 2: Dept Bar -->
                            <div class="bg-white p-5 rounded-2xl border border-slate-100 shadow-sm space-y-4">
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800"><i class="fa-solid fa-chart-bar text-emerald-500 mr-2"></i> จำนวนผู้จัดส่งจำแนกตามกลุ่มสาระการเรียนรู้</h3>
                                <div class="relative h-64 flex justify-center">
                                    <canvas id="chart-depts"></canvas>
                                </div>
                            </div>
                        </div>

                        <!-- DETAILED SUB-TABS SECTION -->
                        <div class="bg-white rounded-2xl border border-slate-100 shadow-sm overflow-hidden">
                            <div class="flex flex-wrap border-b border-slate-100 bg-slate-50/50">
                                <button onclick="switchAdminSubTab('p1')" id="adm-tab-p1" class="flex-1 py-3.5 px-2 text-xs sm:text-sm font-bold border-b-2 border-primary-600 text-primary-600 bg-white whitespace-nowrap">📘 ตอนที่ 1 รายข้อ</button>
                                <button onclick="switchAdminSubTab('p2')" id="adm-tab-p2" class="flex-1 py-3.5 px-2 text-xs sm:text-sm font-bold text-slate-500 border-b-2 border-transparent hover:text-slate-700 hover:bg-slate-100/50 whitespace-nowrap">📙 ตอนที่ 2 รายข้อ</button>
                                <button onclick="switchAdminSubTab('raw')" id="adm-tab-raw" class="flex-1 py-3.5 px-2 text-xs sm:text-sm font-bold text-slate-500 border-b-2 border-transparent hover:text-slate-700 hover:bg-slate-100/50 whitespace-nowrap">📂 ข้อมูลรายบุคคลทั้งหมด</button>
                                <button onclick="switchAdminSubTab('sug')" id="adm-tab-sug" class="flex-1 py-3.5 px-2 text-xs sm:text-sm font-bold text-slate-500 border-b-2 border-transparent hover:text-slate-700 hover:bg-slate-100/50 whitespace-nowrap">📝 ข้อเสนอแนะทั้งหมด</button>
                            </div>

                            <!-- Sub-tab panel 1: Part 1 itemized metrics -->
                            <div id="adm-panel-p1" class="p-6 overflow-x-auto">
                                <table class="w-full text-left border-collapse min-w-[700px]">
                                    <thead>
                                        <tr class="bg-slate-50 text-slate-600 text-[11px] font-bold uppercase border-b border-slate-150">
                                            <th class="py-3 px-4 w-16 text-center">ข้อที่</th>
                                            <th class="py-3 px-4">หัวข้อรายการตามแบบประเมินผลหลักสูตร</th>
                                            <th class="py-3 px-4 w-28 text-right">คะแนนเฉลี่ย</th>
                                            <th class="py-3 px-4 w-48 text-center">แปลระดับคุณภาพ</th>
                                        </tr>
                                    </thead>
                                    <tbody id="table-p1-tbody" class="text-xs sm:text-sm text-slate-700 divide-y divide-slate-100">
                                        <!-- Populated by JavaScript -->
                                    </tbody>
                                </table>
                            </div>

                            <!-- Sub-tab panel 2: Part 2 itemized metrics -->
                            <div id="adm-panel-p2" class="p-6 hidden overflow-x-auto">
                                <table class="w-full text-left border-collapse min-w-[700px]">
                                    <thead>
                                        <tr class="bg-slate-50 text-slate-600 text-[11px] font-bold uppercase border-b border-slate-150">
                                            <th class="py-3 px-4 w-16 text-center">ข้อที่</th>
                                            <th class="py-3 px-4">หัวข้อรายการตามแบบประเมินผลหลักสูตร</th>
                                            <th class="py-3 px-4 w-28 text-right">คะแนนเฉลี่ย</th>
                                            <th class="py-3 px-4 w-48 text-center">แปลระดับคุณภาพ</th>
                                        </tr>
                                    </thead>
                                    <tbody id="table-p2-tbody" class="text-xs sm:text-sm text-slate-700 divide-y divide-slate-100">
                                        <!-- Populated by JavaScript -->
                                    </tbody>
                                </table>
                            </div>

                            <!-- Sub-tab panel 3: Raw user evaluations (Individual Rows) -->
                            <div id="adm-panel-raw" class="p-6 overflow-x-auto hidden">
                                <table class="w-full text-left border-collapse min-w-[1000px]">
                                    <thead>
                                        <tr class="bg-slate-50 text-slate-600 text-[11px] font-bold uppercase border-b border-slate-150">
                                            <th class="py-3 px-4 w-16 text-center">ปีศึกษา</th>
                                            <th class="py-3 px-4 w-32">ประทับเวลา</th>
                                            <th class="py-3 px-4">ชื่อผู้ประเมิน</th>
                                            <th class="py-3 px-4 w-28">ประเภท/ตำแหน่ง</th>
                                            <th class="py-3 px-4 w-32">กลุ่มสาระฯ</th>
                                            <th class="py-3 px-4">รายวิชาสอนหลัก</th>
                                            <th class="py-3 px-4 w-16 text-center">เฉลี่ย P1</th>
                                            <th class="py-3 px-4 w-16 text-center">เฉลี่ย P2</th>
                                            <th class="py-3 px-4 w-28 text-center">การจัดการ</th>
                                        </tr>
                                    </thead>
                                    <tbody id="table-raw-tbody" class="text-xs text-slate-700 divide-y divide-slate-100">
                                        <!-- Populated by JavaScript -->
                                    </tbody>
                                </table>
                            </div>

                            <!-- Sub-tab panel 4: Suggestions aggregated display -->
                            <div id="adm-panel-sug" class="p-6 hidden space-y-6">
                                <div class="border-b border-slate-100 pb-2">
                                    <h4 class="font-bold text-sm text-slate-800"><i class="fa-solid fa-comments text-primary-500 mr-2"></i> รวบรวมข้อเสนอแนะจากการประเมิน</h4>
                                    <p class="text-xs text-slate-500">แสดงความคิดเห็นปรับปรุงทั้งหมดของบุคลากรจำแนกตามรายชื่อผู้ประเมิน</p>
                                </div>
                                <div id="sug-rendered-list" class="space-y-4">
                                    <!-- Populated by JavaScript -->
                                </div>
                            </div>
                        </div>
                    </div>
                </section>
            </div>
        </main>
    </div>

    <!-- INDIVIDUAL DETAILS VIEW MODAL (Feature 2) -->
    <div id="detail-modal" class="fixed inset-0 z-50 flex items-center justify-center bg-black/60 hidden opacity-0 transition-opacity duration-300">
        <div class="bg-white rounded-2xl w-full max-w-4xl max-h-[90vh] overflow-y-auto m-4 shadow-2xl transform scale-95 transition-transform duration-300">
            <!-- Modal Header -->
            <div class="bg-primary-950 text-white p-6 rounded-t-2xl sticky top-0 z-10 flex justify-between items-center">
                <div>
                    <span id="detail-modal-year-badge" class="bg-amber-400 text-primary-950 px-2.5 py-0.5 rounded-full text-[10px] font-black uppercase tracking-wider">ปีการศึกษา 2568</span>
                    <h3 class="text-base sm:text-lg font-bold mt-1"><i class="fa-solid fa-address-card text-amber-400 mr-2"></i> ผลคะแนนประเมินรายบุคคลโดยละเอียด</h3>
                </div>
                <button onclick="closeDetailModal()" class="text-white/80 hover:text-white bg-white/10 hover:bg-white/20 p-2 rounded-lg transition-all">
                    <i class="fa-solid fa-xmark text-xl"></i>
                </button>
            </div>
            <!-- Modal Body -->
            <div class="p-6 space-y-6">
                <!-- Meta Grid -->
                <div class="bg-slate-50 border border-slate-150 p-4 rounded-xl grid grid-cols-1 md:grid-cols-2 gap-4 text-xs sm:text-sm">
                    <div>
                        <p class="text-slate-400 font-semibold uppercase tracking-wider text-[10px]">ชื่อผู้ประเมิน / ครูผู้สอน</p>
                        <p id="detail-modal-name" class="font-extrabold text-slate-900 mt-0.5">...</p>
                    </div>
                    <div>
                        <p class="text-slate-400 font-semibold uppercase tracking-wider text-[10px]">ตำแหน่ง / สิทธิ์ประเมิน</p>
                        <p id="detail-modal-position" class="font-extrabold text-slate-900 mt-0.5">...</p>
                    </div>
                    <div>
                        <p class="text-slate-400 font-semibold uppercase tracking-wider text-[10px]">กลุ่มสาระการเรียนรู้</p>
                        <p id="detail-modal-dept" class="font-extrabold text-slate-900 mt-0.5">...</p>
                    </div>
                    <div>
                        <p class="text-slate-400 font-semibold uppercase tracking-wider text-[10px]">ประทับเวลาจัดส่ง (Timestamp)</p>
                        <p id="detail-modal-time" class="font-medium text-slate-600 mt-0.5">...</p>
                    </div>
                    <div class="md:col-span-2 border-t border-slate-200 pt-3">
                        <p class="text-slate-400 font-semibold uppercase tracking-wider text-[10px] mb-1">รายวิชาที่รับผิดชอบ</p>
                        <ul id="detail-modal-subjects" class="space-y-1 list-disc list-inside font-medium text-slate-700">
                            <!-- Populated dynamically -->
                        </ul>
                    </div>
                </div>

                <!-- Score Accordion Breakdown -->
                <div class="space-y-4">
                    <h4 class="font-extrabold text-slate-800 text-sm border-b border-slate-200 pb-2"><i class="fa-solid fa-chart-line text-primary-500 mr-2"></i> คะแนนประเมินรายข้อแต่ละตอน</h4>
                    
                    <div class="space-y-2">
                        <p class="font-bold text-xs text-primary-900 uppercase">📘 ตอนที่ 1: องค์ประกอบของหลักสูตรสถานศึกษา</p>
                        <div id="detail-modal-p1-list" class="space-y-2">
                            <!-- Dynamic -->
                        </div>
                    </div>

                    <div class="space-y-2 mt-4">
                        <p class="font-bold text-xs text-amber-900 uppercase">📙 ตอนที่ 2: การนำหลักสูตรสถานศึกษาสู่การจัดการเรียนรู้</p>
                        <div id="detail-modal-p2-list" class="space-y-2">
                            <!-- Dynamic -->
                        </div>
                    </div>
                </div>

                <!-- Suggestions Review -->
                <div class="space-y-4 border-t border-slate-200 pt-4">
                    <h4 class="font-extrabold text-slate-800 text-sm pb-1"><i class="fa-solid fa-comments text-amber-500 mr-2"></i> ข้อเสนอแนะและความคิดเห็นส่วนตัว</h4>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                        <div class="bg-blue-50 border border-blue-200 p-3.5 rounded-xl">
                            <p class="font-bold text-xs text-blue-900 mb-1">ตอนที่ 1 (องค์ประกอบหลักสูตร)</p>
                            <p id="detail-modal-sug-p1" class="text-xs text-blue-950 italic">ไม่มีข้อมูลข้อเสนอแนะ</p>
                        </div>
                        <div class="bg-amber-50 border border-amber-200 p-3.5 rounded-xl">
                            <p class="font-bold text-xs text-amber-900 mb-1">ตอนที่ 2 (การนำไปเรียนรู้)</p>
                            <p id="detail-modal-sug-p2" class="text-xs text-amber-950 italic">ไม่มีข้อมูลข้อเสนอแนะ</p>
                        </div>
                        <div class="bg-purple-50 border border-purple-200 p-3.5 rounded-xl">
                            <p class="font-bold text-xs text-purple-900 mb-1">ภาพรวม (พัฒนาปี 2569)</p>
                            <p id="detail-modal-sug-gen" class="text-xs text-purple-950 italic">ไม่มีข้อมูลข้อเสนอแนะ</p>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Modal Footer -->
            <div class="bg-slate-50 px-6 py-4 border-t border-slate-150 flex justify-end">
                <button onclick="closeDetailModal()" class="px-5 py-2 rounded-xl bg-slate-800 text-white font-bold text-xs hover:bg-slate-700 transition-colors shadow-sm">ปิดหน้าต่าง</button>
            </div>
        </div>
    </div>

    <!-- CUSTOM TOAST POPUPS -->
    <div id="custom-toast" class="fixed bottom-6 right-6 z-50 transform translate-y-20 opacity-0 pointer-events-none transition-all duration-300 ease-out">
        <div class="flex items-center space-x-3 bg-slate-900 text-white px-5 py-3.5 rounded-xl shadow-2xl border border-slate-800">
            <span id="toast-icon" class="text-emerald-400 text-lg"><i class="fa-solid fa-circle-check"></i></span>
            <p id="toast-text" class="text-xs sm:text-sm font-semibold">ข้อความระบบ...</p>
        </div>
    </div>

    <!-- CUSTOM CONFIRMATION MODAL FOR RESET -->
    <div id="confirm-modal" class="fixed inset-0 z-50 flex items-center justify-center bg-black/50 hidden opacity-0 transition-opacity duration-300">
        <div class="bg-white rounded-2xl p-6 max-w-md w-full mx-4 shadow-2xl transform scale-95 transition-transform duration-300">
            <h3 class="text-base sm:text-lg font-bold text-slate-800">⚠️ ยืนยันการล้างฐานข้อมูล</h3>
            <p class="text-xs sm:text-sm text-slate-500 mt-2">คุณแน่ใจหรือไม่ว่าต้องการล้างข้อมูลผู้ตอบแบบประเมินทั้งหมดในหน่วยความจำของระบบ? ข้อมูลประวัติการกรอกสะสมทั้งหมดจะถูกลบออกอย่างถาวร</p>
            <div class="mt-6 flex justify-end space-x-3">
                <button onclick="closeConfirmModal()" class="px-4 py-2 text-xs sm:text-sm font-semibold text-slate-600 bg-slate-100 rounded-xl hover:bg-slate-200 transition-colors">ยกเลิก</button>
                <button onclick="executeResetSystem()" class="px-4 py-2 text-xs sm:text-sm font-semibold text-white bg-red-600 rounded-xl hover:bg-red-700 transition-colors">ล้างข้อมูลทั้งหมด</button>
            </div>
        </div>
    </div>

    <!-- CUSTOM ROW DELETE CONFIRMATION MODAL -->
    <div id="delete-confirm-modal" class="fixed inset-0 z-50 flex items-center justify-center bg-black/50 hidden opacity-0 transition-opacity duration-300">
        <div class="bg-white rounded-2xl p-6 max-w-md w-full mx-4 shadow-2xl transform scale-95 transition-transform duration-300">
            <h3 class="text-base sm:text-lg font-bold text-slate-800"><i class="fa-solid fa-trash-can text-red-500 mr-2"></i> ยืนยันการลบข้อมูล</h3>
            <p class="text-xs sm:text-sm text-slate-500 mt-2">คุณแน่ใจหรือไม่ว่าต้องการลบข้อมูลประวัติของ <span id="delete-target-name" class="font-bold text-slate-900"></span>? การลบนี้จะเป็นการถอนสิทธิ์คะแนนออกจากสถิติตลอดไปและไม่สามารถย้อนคืนได้</p>
            <div class="mt-6 flex justify-end space-x-3">
                <button onclick="closeDeleteConfirmModal()" class="px-4 py-2 text-xs sm:text-sm font-semibold text-slate-600 bg-slate-100 rounded-xl hover:bg-slate-200 transition-colors">ยกเลิก</button>
                <button onclick="executeDeleteRecord()" class="px-4 py-2 text-xs sm:text-sm font-semibold text-white bg-red-600 rounded-xl hover:bg-red-700 transition-colors">ลบรายชื่อนี้</button>
            </div>
        </div>
    </div>

    <!-- JAVASCRIPT PROGRAM LOGIC -->
    <script>
        const STORAGE_KEY = "rpw_curriculum_evals_v4.0";
        const ADMIN_SESSION_KEY = "rpw_admin_authorized_v4";
        const EXCEL_FILE_NAME = "Curriculum_Evaluation_MultiYear_Report.xlsx";

        // Structured Mapped categories verbatim from document
        const PART1_STRUCTURE = [
            {
                section: "1. ส่วนนำ",
                questions: [
                    { id: "part1_1_1", title: "1.1 ความนำ", text: "แสดงความเชื่อมโยงระหว่างหลักสูตรแกนกลางการศึกษาขั้นพื้นฐาน พุทธศักราช 2551 (ฉบับปรับปรุง พุทธศักราช 2560) กรอบหลักสูตรระดับท้องถิ่น นโยบาย/จุดเน้น และความต้องการของโรงเรียน" },
                    { id: "part1_1_2", title: "1.2 วิสัยทัศน์", text: "แสดงภาพอนาคตที่พึงประสงค์ของผู้เรียนที่สอดคล้องกับวิสัยทัศน์ของหลักสูตรแกนกลางการศึกษาขั้นพื้นฐาน พุทธศักราช 2551 (ฉบับปรับปรุง พุทธศักราช 2560) อย่างชัดเจน สอดคล้องกับกรอบหลักสูตรระดับท้องถิ่น ครอบคลุมสภาพความต้องการของโรงเรียน ชุมชน ท้องถิ่น มีความชัดเจนสามารถปฏิบัติได้" },
                    { id: "part1_1_3", title: "1.3 สมรรถนะสำคัญของผู้เรียน", text: "มีความสอดคล้องกับหลักสูตรแกนกลางการศึกษาขั้นพื้นฐาน พุทธศักราช 2551 (ฉบับปรับปรุง พุทธศักราช 2560)" },
                    { id: "part1_1_4", title: "1.4 คุณลักษณะอันพึงประสงค์", text: "มีความสอดคล้องกับหลักสูตรแกนกลางการศึกษาขั้นพื้นฐาน พุทธศักราช 2551 สอดคล้องกับเป้าหมาย จุดเน้น กรอบหลักสูตรระดับท้องถิ่นสอดคล้องกับวิสัยทัศน์ ของโรงเรียน" }
                ]
            },
            {
                section: "2. โครงสร้างหลักสูตรสถานศึกษา",
                questions: [
                    { id: "part1_2_1", title: "2.1 โครงสร้างเวลาเรียน", text: "มีการระบุเวลาเรียนตลอดหลักสูตร จำนวน 8 กลุ่มสาระการเรียนรู้ ที่เป็นเวลาเรียนพื้นฐาน และเพิ่มเติมจำแนกแต่ละชั้นปีอย่างชัดเจน ระบุเวลาการจัดกิจกรรมพัฒนาผู้เรียนจำแนกแต่ละชั้นปีอย่างชัดเจน เวลาเรียนรวมของหลักสูตรสถานศึกษาสอดคล้องกับโครงสร้างเวลาเรียนตามหลักสูตรแกนกลางการศึกษาขั้นพื้นฐาน พุทธศักราช 2551 (ฉบับปรับปรุง พุทธศักราช 2560)" },
                    { id: "part1_2_2", title: "2.2 โครงสร้างหลักสูตรชั้นปี", text: "มีการระบุรายวิชาพื้นฐาน รายวิชาเพิ่มเติม ระบุรหัสวิชา ชื่อรายวิชา พร้อมทั้งระบุเวลาเรียน และ/หรือหน่วยกิต มีการระบุกิจกรรมพัฒนาผู้เรียน พร้อมทั้งระบุเวลาเรียนไว้อย่างถูกต้อง ชัดเจน รายวิชาเพิ่มเติม / กิจกรรมเพิ่มเติมที่กำหนดสอดคล้องกับวิสัยทัศน์" }
                ]
            },
            {
                section: "3. คำอธิบายรายวิชา",
                questions: [
                    { id: "part1_3_0", title: "3. คำอธิบายรายวิชา", text: "มีการระบุรหัสวิชา ชื่อรายวิชา และชื่อกลุ่มสาระการเรียนรู้ ชั้นปีที่สอน จำนวนเวลาเรียน และ/หรือหน่วยกิต ไว้อย่างถูกต้องชัดเจน การเขียนคำอธิบายรายวิชาได้เขียนเป็นความเรียงโดยระบุ องค์ความรู้ ทักษะกระบวนการ และคุณลักษณะ หรือเจตคติ ที่ต้องการและครอบคลุมตัวชี้วัด สาระการเรียนรู้แกนกลาง ระบุรหัสตัวชี้วัด ในรายวิชาพื้นฐานและจำนวนรวมของตัวชี้วัดและระบุผลการเรียนรู้ ในรายวิชาเพิ่มเติมและจำนวนรวมของผลการเรียนรู้ถูกต้อง มีการกำหนดสาระการเรียนรู้ท้องถิ่น แหล่งเรียนรู้ท้องถิ่น สอดแทรกอยู่ในคำอธิบายรายวิชาพื้นฐานหรือรายวิชาเพิ่มเติม มีการยืดหยุ่นตามความต้องการ สนใจของผู้เรียน" }
                ]
            },
            {
                section: "4. กิจกรรมพัฒนาผู้เรียน",
                questions: [
                    { id: "part1_4_0", title: "4. กิจกรรมพัฒนาผู้เรียน", text: "ในโครงสร้างหลักสูตรสถานศึกษาและโครงสร้างหลักสูตรชั้นปี ได้ระบุกิจกรรม และจัดเวลา สอน ตามที่กำหนดไว้ในหลักสูตรแกนกลางการศึกษาขั้นพื้นฐานและสอดคล้องกับบริบทของโรงเรียน ในส่วนที่ 4 ของหลักสูตรสถานศึกษามีการจัดทำโครงสร้างและแนวการจัดกิจกรรม แนวทางการวัดและประเมินกิจกรรมพัฒนาผู้เรียนทั้ง 3 กิจกรรมที่ชัดเจน" }
                ]
            },
            {
                section: "5. เกณฑ์การจบการศึกษา",
                questions: [
                    { id: "part1_5_0", title: "5. เกณฑ์การจบการศึกษา", text: "ระบุเวลาเรียน/หน่วยกิต ทั้งรายวิชาพื้นฐานและรายวิชาเพิ่มเติมตามเกณฑ์การจบการศึกษาของโรงเรียน ชัดเจน ระบุเกณฑ์การประเมินการอ่าน คิดวิเคราะห์ และเขียนไว้อย่างชัดเจน ระบุเกณฑ์การประเมินคุณลักษณะอันพึงประสงค์ไว้อย่างชัดเจน ระบุเกณฑ์การผ่านกิจกรรมพัฒนาผู้เรียนไว้อย่างชัดเจน" }
                ]
            }
        ];

        const PART2_STRUCTURE = [
            {
                section: "1. โครงสร้างรายวิชา",
                questions: [
                    { id: "part2_1_1", title: "1.1 การจัดกลุ่มมาตรฐานการเรียนรู้/ตัวชี้วัด", text: "จัดกลุ่มมาตรฐานการเรียนรู้/ตัวชี้วัดที่มีความสัมพันธ์กันและเวลา ในแต่ละหน่วยการเรียนรู้ เหมาะสม ทุกกลุ่มสาระฯ" },
                    { id: "part2_1_2", title: "1.2 การจัดทำสาระสำคัญ/ความคิดรวบยอด", text: "ได้วิเคราะห์แก่นความรู้ของทุกตัวชี้วัดในแต่ละหน่วยการเรียนรู้ มาจัดทำสาระสำคัญ/ความคิดรวบยอด ชัดเจนเหมาะสมและครบทุกหน่วยการเรียนรู้ทุกกลุ่มสาระฯ มีการยืดหยุ่นตามความต้องการ สนใจของผู้เรียน" },
                    { id: "part2_1_3", title: "การตั้งชื่อหน่วยการเรียนรู้ของแต่ละหน่วยการเรียนรู้", text: "สะท้อนให้เห็นสาระสำคัญ หรือประเด็นหลักในหน่วยการเรียนรู้นั้นๆ น่าสนใจเหมาะสมกับวัย ความสนใจ ความสามารถของผู้เรียน ทุกกลุ่มสาระฯ" },
                    { id: "part2_1_4", title: "การกำหนดสัดส่วนเวลาเรียน", text: "กำหนดสัดส่วนเวลาเรียนแต่ละหน่วยการเรียนรู้ เหมาะสม และรวมทุกหน่วยต้องเท่ากับเวลาเรียนตามหลักสูตรทุกกลุ่มสาระฯ" },
                    { id: "part2_1_5", title: "การกำหนดสัดส่วนน้ำหนักคะแนน", text: "กำหนดสัดส่วนน้ำหนักคะแนนแต่ละหน่วยการเรียนรู้เหมาะสมและรวมตลอดปี/ภาคเรียนเท่ากับ 100 คะแนน ทุกกลุ่มสาระฯ" }
                ]
            },
            {
                section: "2. หน่วยการเรียนรู้",
                questions: [
                    { id: "part2_2_1", title: "2.1 การวางแผนจัดทำหน่วยการเรียนรู้", text: "มีการวางแผนออกแบบหน่วยการเรียนรู้ครบทุกหน่วยการเรียนรู้ และทุกกลุ่มสาระฯ โดยใช้แหล่งเรียนรู้ท้องถิ่น เป็นห้องเรียน" },
                    { id: "part2_2_2", title: "2.2 การจัดทำหน่วยการเรียนรู้ : การกำหนดเป้าหมาย", text: "กำหนดมาตรฐานการเรียนรู้/ตัวชี้วัด สาระสำคัญ/ความคิดรวบยอด สาระการเรียนรู้ สมรรถนะสำคัญของผู้เรียน คุณลักษณะอันพึงประสงค์ถูกต้อง เหมาะสมมีความสอดคล้องกัน" },
                    { id: "part2_2_3", title: "2.3 การจัดทำหน่วยการเรียนรู้ : การกำหนดหลักฐานการเรียนรู้", text: "กำหนดชิ้นงาน /ภาระงาน การวัดและประเมินผลสอดคล้องกับตัวชี้วัดและมาตรฐานการเรียนรู้" },
                    { id: "part2_2_4", title: "2.4 การจัดทำหน่วยการเรียนรู้ : ออกแบบกิจกรรมการเรียนรู้", text: "ออกแบบกิจกรรมการเรียนรู้ ได้สอดคล้องกับตัวชี้วัด/มาตรฐาน หลักสูตรท้องถิ่น และเน้นผู้เรียนเป็นสำคัญด้วยกระบวนการเชิงรุก Active Learning" }
                ]
            },
            {
                section: "3. แผนการจัดการเรียนรู้ Active Learning",
                questions: [
                    { id: "part2_3_1", title: "3.1 เขียนแผนการจัดการเรียนรู้ Active Learning", text: "เขียนแผนการจัดการเรียนรู้ Active Learning ที่ ครบตามองค์ประกอบที่สำคัญทุกหน่วยการเรียนรู้ และมีการบูรณาการข้ามกลุ่มสาระการเรียนรู้" },
                    { id: "part2_3_2", title: "3.2 การใช้เทคโนโลยีทางการศึกษาและแหล่งเรียนรู้ท้องถิ่น", text: "มีการใช้เทคโนโลยีทางการศึกษาในการจัดกระบวนการเรียนรู้ และใช้แหล่งเรียนรู้ท้องถิ่น เป็นห้องเรียน" },
                    { id: "part2_3_3", title: "3.3 ความสอดคล้องกับทักษะศตวรรษที่ ๒๑", text: "สอดคล้องจุดเน้นสู่การพัฒนาผู้เรียน ความสามารถและทักษะของผู้เรียนศตวรรษที่ ๒๑ (3Rs x 8Cs x 2Ls)" }
                ]
            },
            {
                section: "4. พัฒนาหลักสูตรการศึกษาอย่างยั่งยืน",
                questions: [
                    { id: "part2_4_1", title: "4.1 การนิเทศการใช้หลักสูตร", text: "มีการนิเทศการใช้หลักสูตรสถานศึกษาอย่างต่อเนื่อง" },
                    { id: "part2_4_2", title: "4.2 การประเมินการใช้หลักสูตร", text: "มีการประเมินการใช้หลักสูตรสถานศึกษาอย่างต่อเนื่อง" },
                    { id: "part2_4_3", title: "4.3 การนำผลประเมินไปวางแผนพัฒนา", text: "นำผลการประเมินการใช้หลักสูตรสถานศึกษามาวางแผนในการพัฒนาหลักสูตรสถานศึกษาอย่างต่อเนื่อง" }
                ]
            }
        ];

        const PART1_QUESTIONS_DATA = PART1_STRUCTURE.reduce((acc, curr) => acc.concat(curr.questions), []);
        const PART2_QUESTIONS_DATA = PART2_STRUCTURE.reduce((acc, curr) => acc.concat(curr.questions), []);

        // Global states
        let evaluationDatabase = [];
        let chartRolesInstance = null;
        let chartDeptsInstance = null;
        let recordToDeleteId = null;
        let isAdminAuthenticated = false;

        window.onload = function() {
            // Load DB or prepopulate demo
            const cached = localStorage.getItem(STORAGE_KEY);
            if (cached) {
                evaluationDatabase = JSON.parse(cached);
            } else {
                loadPrepopulatedMocks();
            }

            // Check if admin is currently authenticated during session
            const authCached = sessionStorage.getItem(ADMIN_SESSION_KEY);
            if (authCached === "true") {
                isAdminAuthenticated = true;
            }

            renderEvaluationQuestions();
            switchTab('form');
            updateAdminPanelData();
        };

        function showToast(message, isSuccess = true) {
            const toast = document.getElementById('custom-toast');
            const icon = document.getElementById('toast-icon');
            const text = document.getElementById('toast-text');

            text.textContent = message;
            if (isSuccess) {
                icon.innerHTML = '<i class="fa-solid fa-circle-check"></i>';
                icon.className = "text-emerald-400 text-lg";
            } else {
                icon.innerHTML = '<i class="fa-solid fa-triangle-exclamation"></i>';
                icon.className = "text-amber-400 text-lg";
            }

            toast.classList.remove('translate-y-20', 'opacity-0', 'pointer-events-none');
            toast.classList.add('translate-y-0', 'opacity-100');

            setTimeout(() => {
                toast.classList.add('translate-y-20', 'opacity-0', 'pointer-events-none');
                toast.classList.remove('translate-y-0', 'opacity-100');
            }, 3500);
        }

        function toggleSidebar() {
            const sidebar = document.getElementById('sidebar');
            sidebar.classList.toggle('-translate-x-full');
        }

        function switchTab(tabId) {
            const pForm = document.getElementById('panel-form');
            const pAdmin = document.getElementById('panel-admin');
            const navForm = document.getElementById('nav-form');
            const navAdmin = document.getElementById('nav-admin');
            const pageTitle = document.getElementById('page-title-header');

            if (tabId === 'form') {
                pForm.classList.remove('hidden');
                pAdmin.classList.add('hidden');
                
                navForm.className = "w-full flex items-center px-4 py-3 text-sm font-medium rounded-xl transition-all duration-200 bg-primary-800 text-white shadow-lg shadow-primary-950/40";
                navAdmin.className = "w-full flex items-center px-4 py-3 text-sm font-medium rounded-xl transition-all duration-200 text-primary-100 hover:bg-primary-800/50 hover:text-white";
                pageTitle.textContent = "กรอกแบบประเมินผลการใช้หลักสูตร";
            } else {
                pForm.classList.add('hidden');
                pAdmin.classList.remove('hidden');
                
                navForm.className = "w-full flex items-center px-4 py-3 text-sm font-medium rounded-xl transition-all duration-200 text-primary-100 hover:bg-primary-800/50 hover:text-white";
                navAdmin.className = "w-full flex items-center px-4 py-3 text-sm font-medium rounded-xl transition-all duration-200 bg-primary-800 text-white shadow-lg shadow-primary-950/40";
                pageTitle.textContent = "แผงควบคุมและระบบวิเคราะห์สถิติหลักสูตร (Admin)";
                
                renderAdminSecurityStatus();
            }

            const sidebar = document.getElementById('sidebar');
            if (!sidebar.classList.contains('-translate-x-full') && window.innerWidth < 768) {
                sidebar.classList.add('-translate-x-full');
            }
        }

        function renderAdminSecurityStatus() {
            const lobby = document.getElementById('admin-login-lobby');
            const content = document.getElementById('admin-authenticated-content');
            
            if (isAdminAuthenticated) {
                lobby.classList.add('hidden');
                content.classList.remove('hidden');
                updateAdminPanelData();
            } else {
                lobby.classList.remove('hidden');
                content.classList.add('hidden');
                document.getElementById('admin-password-input').value = '';
            }
        }

        function togglePasswordVisibility() {
            const input = document.getElementById('admin-password-input');
            const icon = document.getElementById('password-toggle-icon');
            if (input.type === 'password') {
                input.type = 'text';
                icon.className = 'fa-solid fa-eye-slash text-xs';
            } else {
                input.type = 'password';
                icon.className = 'fa-solid fa-eye text-xs';
            }
        }

        function attemptAdminLogin() {
            const password = document.getElementById('admin-password-input').value;
            if (password === 'admin1234') {
                isAdminAuthenticated = true;
                sessionStorage.setItem(ADMIN_SESSION_KEY, "true");
                showToast("🔑 เข้าสู่ระบบแอดมินวิชาการสำเร็จ!");
                renderAdminSecurityStatus();
            } else {
                showToast("❌ รหัสผ่านแอดมินไม่ถูกต้อง กรุณาลองใหม่อีกครั้ง", false);
            }
        }

        function triggerAdminLogout() {
            isAdminAuthenticated = false;
            sessionStorage.removeItem(ADMIN_SESSION_KEY);
            showToast("🔒 ออกจากระบบความปลอดภัยแอดมินเรียบร้อย");
            renderAdminSecurityStatus();
        }

        function switchFormStep(stepNum) {
            for (let i = 1; i <= 4; i++) {
                document.getElementById(`step-container-${i}`).classList.add('hidden');
                document.getElementById(`step-btn-${i}`).className = "px-4 py-2.5 text-xs sm:text-sm font-bold rounded-lg bg-white text-slate-600 border border-slate-200 hover:bg-slate-50 transition-all";
            }
            document.getElementById(`step-container-${stepNum}`).classList.remove('hidden');
            document.getElementById(`step-btn-${stepNum}`).className = "px-4 py-2.5 text-xs sm:text-sm font-bold rounded-lg bg-primary-600 text-white shadow-md transition-all";
        }

        function renderEvaluationQuestions() {
            const p1 = document.getElementById('part1-questions-render');
            const p2 = document.getElementById('part2-questions-render');

            p1.innerHTML = '';
            p2.innerHTML = '';

            // Render Part 1 Questions by Category Sections
            PART1_STRUCTURE.forEach(sectionBlock => {
                const secHeaderHtml = `
                    <div class="bg-primary-900/10 text-primary-950 px-4 py-2.5 rounded-xl font-bold text-xs sm:text-sm my-5 border-l-4 border-primary-600 shadow-sm flex items-center justify-between">
                        <span><i class="fa-solid fa-folder-open text-primary-600 mr-2"></i> ${sectionBlock.section}</span>
                    </div>
                `;
                p1.insertAdjacentHTML('beforeend', secHeaderHtml);

                sectionBlock.questions.forEach(q => {
                    const qHtml = `
                        <div class="py-4 px-4 bg-slate-50/50 border border-slate-100 rounded-xl mb-4 hover:bg-white hover:border-primary-100 transition-all">
                            <div class="flex flex-col sm:flex-row sm:items-start mb-3 gap-2">
                                <span class="inline-flex px-2.5 py-1 text-[11px] font-extrabold rounded-lg bg-primary-100 text-primary-800 border border-primary-200 shrink-0 self-start">
                                    ${q.title}
                                </span>
                                <p class="text-xs sm:text-sm font-semibold text-slate-800 leading-relaxed">${q.text}</p>
                            </div>
                            <div class="flex flex-wrap gap-2 items-center">
                                <span class="text-[11px] font-bold text-slate-400 mr-2 uppercase">ระบุระดับคุณภาพ:</span>
                                <div class="inline-flex rounded-xl border border-slate-200 bg-white p-1 flex-wrap shadow-sm">
                                    <label class="flex items-center px-3 py-1.5 cursor-pointer rounded-lg hover:bg-slate-50 transition-all">
                                        <input type="radio" name="${q.id}" value="4" checked class="accent-primary-600 w-4 h-4 mr-1.5">
                                        <span class="text-xs font-semibold text-slate-700">4 (ดีเยี่ยม)</span>
                                    </label>
                                    <label class="flex items-center px-3 py-1.5 cursor-pointer rounded-lg hover:bg-slate-50 transition-all">
                                        <input type="radio" name="${q.id}" value="3" class="accent-primary-600 w-4 h-4 mr-1.5">
                                        <span class="text-xs font-semibold text-slate-700">3 (ดี)</span>
                                    </label>
                                    <label class="flex items-center px-3 py-1.5 cursor-pointer rounded-lg hover:bg-slate-50 transition-all">
                                        <input type="radio" name="${q.id}" value="2" class="accent-primary-600 w-4 h-4 mr-1.5">
                                        <span class="text-xs font-semibold text-slate-700">2 (พอใช้)</span>
                                    </label>
                                    <label class="flex items-center px-3 py-1.5 cursor-pointer rounded-lg hover:bg-slate-50 transition-all">
                                        <input type="radio" name="${q.id}" value="1" class="accent-primary-600 w-4 h-4 mr-1.5">
                                        <span class="text-xs font-semibold text-slate-700">1 (ปรับปรุง)</span>
                                    </label>
                                </div>
                            </div>
                        </div>
                    `;
                    p1.insertAdjacentHTML('beforeend', qHtml);
                });
            });

            // Render Part 2 Questions by Category Sections
            PART2_STRUCTURE.forEach(sectionBlock => {
                const secHeaderHtml = `
                    <div class="bg-primary-900/10 text-primary-950 px-4 py-2.5 rounded-xl font-bold text-xs sm:text-sm my-5 border-l-4 border-primary-600 shadow-sm flex items-center justify-between">
                        <span><i class="fa-solid fa-folder-open text-primary-600 mr-2"></i> ${sectionBlock.section}</span>
                    </div>
                `;
                p2.insertAdjacentHTML('beforeend', secHeaderHtml);

                sectionBlock.questions.forEach(q => {
                    const qHtml = `
                        <div class="py-4 px-4 bg-slate-50/50 border border-slate-100 rounded-xl mb-4 hover:bg-white hover:border-primary-100 transition-all">
                            <div class="flex flex-col sm:flex-row sm:items-start mb-3 gap-2">
                                <span class="inline-flex px-2.5 py-1 text-[11px] font-extrabold rounded-lg bg-amber-100 text-amber-800 border border-amber-200 shrink-0 self-start">
                                    ${q.title}
                                </span>
                                <p class="text-xs sm:text-sm font-semibold text-slate-800 leading-relaxed">${q.text}</p>
                            </div>
                            <div class="flex flex-wrap gap-2 items-center">
                                <span class="text-[11px] font-bold text-slate-400 mr-2 uppercase">ระบุระดับคุณภาพ:</span>
                                <div class="inline-flex rounded-xl border border-slate-200 bg-white p-1 flex-wrap shadow-sm">
                                    <label class="flex items-center px-3 py-1.5 cursor-pointer rounded-lg hover:bg-slate-50 transition-all">
                                        <input type="radio" name="${q.id}" value="4" checked class="accent-primary-600 w-4 h-4 mr-1.5">
                                        <span class="text-xs font-semibold text-slate-700">4 (ดีเยี่ยม)</span>
                                    </label>
                                    <label class="flex items-center px-3 py-1.5 cursor-pointer rounded-lg hover:bg-slate-50 transition-all">
                                        <input type="radio" name="${q.id}" value="3" class="accent-primary-600 w-4 h-4 mr-1.5">
                                        <span class="text-xs font-semibold text-slate-700">3 (ดี)</span>
                                    </label>
                                    <label class="flex items-center px-3 py-1.5 cursor-pointer rounded-lg hover:bg-slate-50 transition-all">
                                        <input type="radio" name="${q.id}" value="2" class="accent-primary-600 w-4 h-4 mr-1.5">
                                        <span class="text-xs font-semibold text-slate-700">2 (พอใช้)</span>
                                    </label>
                                    <label class="flex items-center px-3 py-1.5 cursor-pointer rounded-lg hover:bg-slate-50 transition-all">
                                        <input type="radio" name="${q.id}" value="1" class="accent-primary-600 w-4 h-4 mr-1.5">
                                        <span class="text-xs font-semibold text-slate-700">1 (ปรับปรุง)</span>
                                    </label>
                                </div>
                            </div>
                        </div>
                    `;
                    p2.insertAdjacentHTML('beforeend', qHtml);
                });
            });
        }

        function handleFormSubmit(event) {
            event.preventDefault();

            const year = document.getElementById('evaluator-year').value;
            const name = document.getElementById('evaluator-name').value.trim();
            const position = document.getElementById('evaluator-position').value;
            const dept = document.getElementById('evaluator-department').value;

            const s1_code = document.getElementById('subj1-code').value.trim().toUpperCase();
            const s1_name = document.getElementById('subj1-name').value.trim();
            const s1_grade = document.getElementById('subj1-grade').value.trim();

            const s2_code = document.getElementById('subj2-code').value.trim().toUpperCase();
            const s2_name = document.getElementById('subj2-name').value.trim();
            const s2_grade = document.getElementById('subj2-grade').value.trim();

            const s3_code = document.getElementById('subj3-code').value.trim().toUpperCase();
            const s3_name = document.getElementById('subj3-name').value.trim();
            const s3_grade = document.getElementById('subj3-grade').value.trim();

            if (!name) {
                showToast("❌ กรุณากรอกชื่อผู้ประเมิน", false);
                switchFormStep(1);
                return;
            }
            if (!s1_code || !s1_name || !s1_grade) {
                showToast("❌ กรุณากรอกรายวิชาสอนหลักที่ 1 ให้ครบถ้วน", false);
                switchFormStep(1);
                return;
            }

            // Read answers dynamically
            const answers = {};
            PART1_QUESTIONS_DATA.forEach(q => {
                const selected = document.querySelector(`input[name="${q.id}"]:checked`);
                answers[q.id] = parseInt(selected ? selected.value : 4);
            });
            PART2_QUESTIONS_DATA.forEach(q => {
                const selected = document.querySelector(`input[name="${q.id}"]:checked`);
                answers[q.id] = parseInt(selected ? selected.value : 4);
            });

            const suggestionsP1 = document.getElementById('suggestions-part1').value.trim();
            const suggestionsP2 = document.getElementById('suggestions-part2').value.trim();
            const suggestionsGeneral = document.getElementById('suggestions-general').value.trim();

            const record = {
                id: "rec_" + Date.now() + "_" + Math.floor(Math.random() * 1000),
                Timestamp: new Date().toLocaleString('th-TH'),
                Academic_Year: year,
                Evaluator_Name: name,
                Position: position,
                Department: dept,
                Subject1_Code: s1_code,
                Subject1_Name: s1_name,
                Subject1_Grade: s1_grade,
                Subject2_Code: s2_code || "",
                Subject2_Name: s2_name || "",
                Subject2_Grade: s2_grade || "",
                Subject3_Code: s3_code || "",
                Subject3_Name: s3_name || "",
                Subject3_Grade: s3_grade || "",
                ...answers,
                Suggestions_Part1: suggestionsP1,
                Suggestions_Part2: suggestionsP2,
                General_Suggestions: suggestionsGeneral
            };

            evaluationDatabase.push(record);
            localStorage.setItem(STORAGE_KEY, JSON.stringify(evaluationDatabase));

            showToast(`🎉 ระบบบันทึกแบบประเมินหลักสูตร ปีการศึกษา ${year} เรียบร้อยแล้ว!`);
            
            // Clean Form & Redirect to first page
            document.getElementById('evaluation-form').reset();
            switchFormStep(1);
            updateAdminPanelData();
        }

        function getQualityBadge(score) {
            if (score >= 3.50) {
                return { text: "ระดับ 4 (ดีเยี่ยม)", color: "bg-emerald-100 text-emerald-800 border-emerald-200" };
            } else if (score >= 2.50) {
                return { text: "ระดับ 3 (ดี)", color: "bg-blue-100 text-blue-800 border-blue-200" };
            } else if (score >= 1.50) {
                return { text: "ระดับ 2 (พอใช้)", color: "bg-amber-100 text-amber-800 border-amber-200" };
            } else {
                return { text: "ระดับ 1 (ปรับปรุง)", color: "bg-red-100 text-red-800 border-red-200" };
            }
        }

        function handleYearFilterChange() {
            updateAdminPanelData();
        }

        function getFilteredDatabase() {
            const selectedYear = document.getElementById('admin-year-filter').value;
            if (selectedYear === "ทั้งหมด") {
                return evaluationDatabase;
            } else {
                return evaluationDatabase.filter(row => row.Academic_Year === selectedYear);
            }
        }

        function updateAdminPanelData() {
            const filteredData = getFilteredDatabase();
            const count = filteredData.length;
            document.getElementById('stat-total-count').textContent = count;

            if (count === 0) {
                document.getElementById('stat-p1-avg').textContent = "0.00 / 4";
                document.getElementById('stat-p2-avg').textContent = "0.00 / 4";
                document.getElementById('stat-overall-avg').textContent = "0.00 / 4";
                renderCharts(filteredData);
                renderTables(filteredData);
                renderSuggestionsList(filteredData);
                return;
            }

            let p1Sum = 0;
            let p2Sum = 0;

            filteredData.forEach(row => {
                PART1_QUESTIONS_DATA.forEach(q => p1Sum += row[q.id] || 0);
                PART2_QUESTIONS_DATA.forEach(q => p2Sum += row[q.id] || 0);
            });

            const p1Avg = p1Sum / (count * PART1_QUESTIONS_DATA.length);
            const p2Avg = p2Sum / (count * PART2_QUESTIONS_DATA.length);
            const overallAvg = (p1Avg + p2Avg) / 2;

            document.getElementById('stat-p1-avg').textContent = `${p1Avg.toFixed(2)} / 4`;
            document.getElementById('stat-p2-avg').textContent = `${p2Avg.toFixed(2)} / 4`;
            document.getElementById('stat-overall-avg').textContent = `${overallAvg.toFixed(2)} / 4`;

            renderCharts(filteredData);
            renderTables(filteredData);
            renderSuggestionsList(filteredData);
        }

        function switchAdminSubTab(subTabId) {
            const tabs = ['p1', 'p2', 'raw', 'sug'];
            tabs.forEach(t => {
                document.getElementById(`adm-panel-${t}`).classList.add('hidden');
                document.getElementById(`adm-tab-${t}`).className = "flex-1 py-3.5 px-2 text-xs sm:text-sm font-bold text-slate-500 border-b-2 border-transparent hover:text-slate-700 hover:bg-slate-100/50 whitespace-nowrap";
            });

            document.getElementById(`adm-panel-${subTabId}`).classList.remove('hidden');
            document.getElementById(`adm-tab-${subTabId}`).className = "flex-1 py-3.5 px-2 text-xs sm:text-sm font-bold border-b-2 border-primary-600 text-primary-600 bg-white whitespace-nowrap";
        }

        function renderTables(filteredData) {
            const tbody1 = document.getElementById('table-p1-tbody');
            const tbody2 = document.getElementById('table-p2-tbody');
            const tbodyRaw = document.getElementById('table-raw-tbody');

            tbody1.innerHTML = '';
            tbody2.innerHTML = '';
            tbodyRaw.innerHTML = '';

            const count = filteredData.length;

            // ตอนที่ 1 table
            PART1_QUESTIONS_DATA.forEach((q, index) => {
                let sum = 0;
                filteredData.forEach(row => sum += row[q.id] || 0);
                const avg = count > 0 ? (sum / count) : 0;
                const badge = getQualityBadge(avg);

                const html = `
                    <tr class="hover:bg-slate-50/80 transition-colors">
                        <td class="py-3.5 px-4 text-center font-bold text-slate-400">${index + 1}</td>
                        <td class="py-3.5 px-4 text-slate-800 text-xs sm:text-sm leading-relaxed">
                            <span class="font-black text-primary-900 block mb-0.5 mb-1">${q.title}</span>
                            <span class="text-slate-500 text-xs block leading-relaxed">${q.text}</span>
                        </td>
                        <td class="py-3.5 px-4 text-right font-extrabold text-primary-600">${avg.toFixed(2)}</td>
                        <td class="py-3.5 px-4 text-center">
                            <span class="inline-flex px-2.5 py-1 rounded-full text-[10px] font-bold border ${badge.color}">${badge.text}</span>
                        </td>
                    </tr>
                `;
                tbody1.insertAdjacentHTML('beforeend', html);
            });

            // ตอนที่ 2 table
            PART2_QUESTIONS_DATA.forEach((q, index) => {
                let sum = 0;
                filteredData.forEach(row => sum += row[q.id] || 0);
                const avg = count > 0 ? (sum / count) : 0;
                const badge = getQualityBadge(avg);

                const html = `
                    <tr class="hover:bg-slate-50/80 transition-colors">
                        <td class="py-3.5 px-4 text-center font-bold text-slate-400">${index + 1}</td>
                        <td class="py-3.5 px-4 text-slate-800 text-xs sm:text-sm leading-relaxed">
                            <span class="font-black text-amber-800 block mb-0.5 mb-1">${q.title}</span>
                            <span class="text-slate-500 text-xs block leading-relaxed">${q.text}</span>
                        </td>
                        <td class="py-3.5 px-4 text-right font-extrabold text-primary-600">${avg.toFixed(2)}</td>
                        <td class="py-3.5 px-4 text-center">
                            <span class="inline-flex px-2.5 py-1 rounded-full text-[10px] font-bold border ${badge.color}">${badge.text}</span>
                        </td>
                    </tr>
                `;
                tbody2.insertAdjacentHTML('beforeend', html);
            });

            // Raw entries table with Action Buttons (View & Delete)
            filteredData.forEach(row => {
                let p1Sum = 0;
                let p2Sum = 0;
                PART1_QUESTIONS_DATA.forEach(q => p1Sum += row[q.id] || 0);
                PART2_QUESTIONS_DATA.forEach(q => p2Sum += row[q.id] || 0);

                const p1Avg = (p1Sum / PART1_QUESTIONS_DATA.length).toFixed(2);
                const p2Avg = (p2Sum / PART2_QUESTIONS_DATA.length).toFixed(2);

                const subs = [
                    row.Subject1_Code ? `${row.Subject1_Code} (${row.Subject1_Grade})` : '',
                    row.Subject2_Code ? `${row.Subject2_Code} (${row.Subject2_Grade})` : '',
                    row.Subject3_Code ? `${row.Subject3_Code} (${row.Subject3_Grade})` : ''
                ].filter(Boolean).join(', ');

                const html = `
                    <tr class="hover:bg-slate-50/80 transition-all">
                        <td class="py-3 px-4 text-center"><span class="bg-slate-200 text-slate-800 px-2 py-0.5 rounded-md font-bold text-[11px]">${row.Academic_Year}</span></td>
                        <td class="py-3 px-4 text-slate-400 font-medium whitespace-nowrap text-[11px]">${row.Timestamp}</td>
                        <td class="py-3 px-4 font-bold text-slate-800">${row.Evaluator_Name}</td>
                        <td class="py-3 px-4 text-slate-600 text-xs">${row.Position}</td>
                        <td class="py-3 px-4 text-slate-600 text-xs">${row.Department}</td>
                        <td class="py-3 px-4 text-slate-500 text-xs truncate max-w-[200px]" title="${subs}">${subs}</td>
                        <td class="py-3 px-4 text-center font-black text-emerald-600">${p1Avg}</td>
                        <td class="py-3 px-4 text-center font-black text-teal-600">${p2Avg}</td>
                        <td class="py-3 px-4 text-center whitespace-nowrap space-x-1">
                            <button onclick="openDetailModal('${row.id}')" class="p-1.5 text-blue-600 hover:text-blue-800 hover:bg-blue-50 rounded-lg transition-colors inline-flex items-center" title="ดูรายละเอียดคำตอบ">
                                <i class="fa-solid fa-eye mr-1"></i> ดูคำตอบ
                            </button>
                            <button onclick="confirmDeleteRecord('${row.id}')" class="p-1.5 text-red-500 hover:text-red-700 hover:bg-red-50 rounded-lg transition-colors inline-flex items-center" title="ลบแบบประเมินรายนี้">
                                <i class="fa-solid fa-trash-can"></i>
                            </button>
                        </td>
                    </tr>
                `;
                tbodyRaw.insertAdjacentHTML('beforeend', html);
            });
        }

        function renderSuggestionsList(filteredData) {
            const listContainer = document.getElementById('sug-rendered-list');
            listContainer.innerHTML = '';

            const dataWithSuggestions = filteredData.filter(row => 
                (row.Suggestions_Part1 && row.Suggestions_Part1.trim() !== '') ||
                (row.Suggestions_Part2 && row.Suggestions_Part2.trim() !== '') ||
                (row.General_Suggestions && row.General_Suggestions.trim() !== '')
            );

            if (dataWithSuggestions.length === 0) {
                listContainer.innerHTML = `
                    <div class="text-center py-8 bg-slate-50 rounded-xl border border-dashed border-slate-200">
                        <p class="text-xs text-slate-400">ไม่มีข้อมูลข้อเสนอแนะที่ส่งเข้ามาในปีการศึกษานี้</p>
                    </div>
                `;
                return;
            }

            dataWithSuggestions.forEach(row => {
                const sugHtml = `
                    <div class="p-5 bg-white border border-slate-150 rounded-xl shadow-sm space-y-3">
                        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-100 pb-2">
                            <div class="flex items-center space-x-2">
                                <span class="bg-primary-100 text-primary-900 px-2 py-0.5 rounded text-[10px] font-extrabold uppercase">ปีศึกษา ${row.Academic_Year}</span>
                                <span class="font-extrabold text-xs text-slate-800">${row.Evaluator_Name} (${row.Position})</span>
                            </div>
                            <span class="text-[10px] text-slate-400">${row.Timestamp}</span>
                        </div>
                        <div class="grid grid-cols-1 md:grid-cols-3 gap-3 text-xs">
                            ${row.Suggestions_Part1 ? `
                                <div class="p-3 bg-blue-50/50 border border-blue-100 rounded-lg">
                                    <p class="font-bold text-blue-900 mb-1">ตอนที่ 1 (องค์ประกอบหลักสูตร)</p>
                                    <p class="text-slate-700 leading-relaxed italic">"${row.Suggestions_Part1}"</p>
                                </div>
                            ` : '<div class="p-3 bg-slate-50 text-slate-400 rounded-lg italic">ไม่มีคำแนะนำส่วนนำ/โครงสร้าง</div>'}
                            
                            ${row.Suggestions_Part2 ? `
                                <div class="p-3 bg-amber-50/50 border border-amber-100 rounded-lg">
                                    <p class="font-bold text-amber-900 mb-1">ตอนที่ 2 (การนำไปเรียนรู้)</p>
                                    <p class="text-slate-700 leading-relaxed italic">"${row.Suggestions_Part2}"</p>
                                </div>
                            ` : '<div class="p-3 bg-slate-50 text-slate-400 rounded-lg italic">ไม่มีคำแนะนำการนำไปสอน</div>'}
                            
                            ${row.General_Suggestions ? `
                                <div class="p-3 bg-purple-50/50 border border-purple-100 rounded-lg">
                                    <p class="font-bold text-purple-900 mb-1">ภาพรวม (ข้อเสนอแนะทั่วไป)</p>
                                    <p class="text-slate-700 leading-relaxed italic">"${row.General_Suggestions}"</p>
                                </div>
                            ` : '<div class="p-3 bg-slate-50 text-slate-400 rounded-lg italic">ไม่มีข้อเสนอแนะภาพรวม</div>'}
                        </div>
                    </div>
                `;
                listContainer.insertAdjacentHTML('beforeend', sugHtml);
            });
        }

        function renderCharts(filteredData) {
            const rolesMap = { "ครู": 0, "ผู้อำนวยการโรงเรียน": 0, "รองผู้อำนวยการโรงเรียน": 0, "บุคลากรทางการศึกษาอื่นๆ": 0 };
            const deptsMap = {
                "วิทยาศาสตร์และเทคโนโลยี": 0, "คณิตศาสตร์": 0, "ภาษาไทย": 0, "ภาษาต่างประเทศ": 0,
                "สังคมศึกษา ศาสนา และวัฒนธรรม": 0, "สุขศึกษาและพลศึกษา": 0, "ศิลปะ": 0, "การงานอาชีพ": 0
            };

            filteredData.forEach(row => {
                if (rolesMap[row.Position] !== undefined) rolesMap[row.Position]++;
                if (deptsMap[row.Department] !== undefined) deptsMap[row.Department]++;
            });

            // Destruct overlays
            if (chartRolesInstance) chartRolesInstance.destroy();
            if (chartDeptsInstance) chartDeptsInstance.destroy();

            // Roles Chart Drawing
            const ctxRoles = document.getElementById('chart-roles').getContext('2d');
            chartRolesInstance = new Chart(ctxRoles, {
                type: 'doughnut',
                data: {
                    labels: Object.keys(rolesMap),
                    datasets: [{
                        data: Object.values(rolesMap),
                        backgroundColor: ['#2563eb', '#10b981', '#f59e0b', '#64748b'],
                        borderWidth: 2,
                        borderColor: '#ffffff'
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: { position: 'bottom', labels: { boxWidth: 10, font: { family: 'Sarabun', size: 10 } } }
                    }
                }
            });

            // Depts Chart Drawing
            const ctxDepts = document.getElementById('chart-depts').getContext('2d');
            chartDeptsInstance = new Chart(ctxDepts, {
                type: 'bar',
                data: {
                    labels: Object.keys(deptsMap).map(k => k.length > 15 ? k.substring(0, 15) + '...' : k),
                    datasets: [{
                        label: 'จำนวนคน',
                        data: Object.values(deptsMap),
                        backgroundColor: '#10b981',
                        borderRadius: 6
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: { legend: { display: false } },
                    scales: { y: { beginAtZero: true, ticks: { precision: 0 } } }
                }
            });
        }

        function openDetailModal(id) {
            const record = evaluationDatabase.find(r => r.id === id);
            if (!record) return;

            document.getElementById('detail-modal-year-badge').textContent = `ปีการศึกษา ${record.Academic_Year}`;
            document.getElementById('detail-modal-name').textContent = record.Evaluator_Name;
            document.getElementById('detail-modal-position').textContent = record.Position;
            document.getElementById('detail-modal-dept').textContent = record.Department;
            document.getElementById('detail-modal-time').textContent = record.Timestamp;

            // Render subjects list
            const subList = document.getElementById('detail-modal-subjects');
            subList.innerHTML = '';
            const subs = [
                record.Subject1_Code ? `รายวิชาหลัก: ${record.Subject1_Code} ${record.Subject1_Name} (${record.Subject1_Grade})` : null,
                record.Subject2_Code ? `รายวิชาเพิ่มเติม: ${record.Subject2_Code} ${record.Subject2_Name} (${record.Subject2_Grade})` : null,
                record.Subject3_Code ? `รายวิชาร่วมสอน: ${record.Subject3_Code} ${record.Subject3_Name} (${record.Subject3_Grade})` : null
            ].filter(Boolean);
            
            if (subs.length === 0) {
                subList.innerHTML = '<li class="text-xs text-slate-400 italic">ไม่มีข้อมูลรายวิชาที่ระบุ</li>';
            } else {
                subs.forEach(s => {
                    subList.insertAdjacentHTML('beforeend', `<li class="text-xs text-slate-700">${s}</li>`);
                });
            }

            // Render Suggestions
            document.getElementById('detail-modal-sug-p1').textContent = record.Suggestions_Part1 ? `"${record.Suggestions_Part1}"` : "ไม่มีข้อมูลข้อเสนอแนะ";
            document.getElementById('detail-modal-sug-p2').textContent = record.Suggestions_Part2 ? `"${record.Suggestions_Part2}"` : "ไม่มีข้อมูลข้อเสนอแนะ";
            document.getElementById('detail-modal-sug-gen').textContent = record.General_Suggestions ? `"${record.General_Suggestions}"` : "ไม่มีข้อมูลข้อเสนอแนะ";

            // Render Part 1 questions and answers
            const p1List = document.getElementById('detail-modal-p1-list');
            p1List.innerHTML = '';
            PART1_QUESTIONS_DATA.forEach(q => {
                const ansValue = record[q.id] || 4;
                const scoreBadge = getScoreDisplayColor(ansValue);
                p1List.insertAdjacentHTML('beforeend', `
                    <div class="flex items-center justify-between p-2.5 rounded-lg border border-slate-150 bg-slate-50/50 text-xs">
                        <div class="max-w-[75%]">
                            <p class="font-extrabold text-slate-800">${q.title}</p>
                            <p class="text-slate-500 truncate text-[10px] mt-0.5" title="${q.text}">${q.text}</p>
                        </div>
                        <span class="inline-flex px-2 py-0.5 rounded-md font-extrabold border ${scoreBadge.color}">${ansValue} (${scoreBadge.text})</span>
                    </div>
                `);
            });

            // Render Part 2 questions and answers
            const p2List = document.getElementById('detail-modal-p2-list');
            p2List.innerHTML = '';
            PART2_QUESTIONS_DATA.forEach(q => {
                const ansValue = record[q.id] || 4;
                const scoreBadge = getScoreDisplayColor(ansValue);
                p2List.insertAdjacentHTML('beforeend', `
                    <div class="flex items-center justify-between p-2.5 rounded-lg border border-slate-150 bg-slate-50/50 text-xs">
                        <div class="max-w-[75%]">
                            <p class="font-extrabold text-amber-900">${q.title}</p>
                            <p class="text-slate-500 truncate text-[10px] mt-0.5" title="${q.text}">${q.text}</p>
                        </div>
                        <span class="inline-flex px-2 py-0.5 rounded-md font-extrabold border ${scoreBadge.color}">${ansValue} (${scoreBadge.text})</span>
                    </div>
                `);
            });

            // Open Modal
            const modal = document.getElementById('detail-modal');
            modal.classList.remove('hidden');
            setTimeout(() => {
                modal.classList.remove('opacity-0');
                modal.querySelector('div').classList.remove('scale-95');
            }, 50);
        }

        function getScoreDisplayColor(val) {
            switch(val) {
                case 4: return { text: "ดีเยี่ยม", color: "bg-emerald-50 border-emerald-200 text-emerald-800" };
                case 3: return { text: "ดี", color: "bg-blue-50 border-blue-200 text-blue-800" };
                case 2: return { text: "พอใช้", color: "bg-amber-50 border-amber-200 text-amber-800" };
                case 1: return { text: "ปรับปรุง", color: "bg-red-50 border-red-200 text-red-800" };
                default: return { text: "ดีเยี่ยม", color: "bg-emerald-50 border-emerald-200 text-emerald-800" };
            }
        }

        function closeDetailModal() {
            const modal = document.getElementById('detail-modal');
            modal.classList.add('opacity-0');
            modal.querySelector('div').classList.add('scale-95');
            setTimeout(() => {
                modal.classList.add('hidden');
            }, 300);
        }

        function triggerExcelDownload() {
            const filteredData = getFilteredDatabase();
            if (filteredData.length === 0) {
                showToast("❌ ไม่มีข้อมูลสำหรับการประมวลผลเป็น Excel", false);
                return;
            }

            const selectedYear = document.getElementById('admin-year-filter').value;
            const wb = XLSX.utils.book_new();

            // Sheet 1: Dashboard metrics
            const count = filteredData.length;
            let p1Sum = 0, p2Sum = 0;
            filteredData.forEach(row => {
                PART1_QUESTIONS_DATA.forEach(q => p1Sum += row[q.id] || 0);
                PART2_QUESTIONS_DATA.forEach(q => p2Sum += row[q.id] || 0);
            });
            const p1Avg = p1Sum / (count * PART1_QUESTIONS_DATA.length);
            const p2Avg = p2Sum / (count * PART2_QUESTIONS_DATA.length);
            const overallAvg = (p1Avg + p2Avg) / 2;

            const dashData = [
                ["รายงานสรุปผลการประเมินหลักสูตรสถานศึกษา โรงเรียนรัฐประชาวิทยาคาร"],
                [`สรุปสถิติตามตัวกรอง: ${selectedYear === "ทั้งหมด" ? "ทุกปีการศึกษา" : "ปีการศึกษา " + selectedYear}`],
                [],
                ["สรุปดัชนีชี้วัดหลัก", "ค่าที่วัดได้"],
                ["จำนวนผู้จัดส่งแบบประเมินรวมสะสม (คน)", count],
                ["คะแนนประเมินเฉลี่ยสะสม ตอนที่ 1 (เต็ม 4.00)", parseFloat(p1Avg.toFixed(2))],
                ["คะแนนประเมินเฉลี่ยสะสม ตอนที่ 2 (เต็ม 4.00)", parseFloat(p2Avg.toFixed(2))],
                ["ค่าเฉลี่ยสถิติภาพรวมหลักสูตรทั้งระบบ", parseFloat(overallAvg.toFixed(2))],
                ["ผลประเมินแปลคุณภาพเชิงสถิติ", getQualityBadge(overallAvg).text],
                [],
                ["อ้างอิงเอกสารโครงสร้างข้อมูลต้นฉบับ", "ตัวอย่าง แบบประเมินหลักสูตร_2.docx"]
            ];
            const wsDash = XLSX.utils.aoa_to_sheet(dashData);
            XLSX.utils.book_append_sheet(wb, wsDash, "สรุปผลภาพรวม (Dashboard)");

            // Sheet 2: Part 1 Averages
            const p1Data = [
                ["ข้อที่", "หัวข้อรายการและประเด็นเกณฑ์ประเมิน ตอนที่ 1", "ค่าน้ำหนักคะแนนเฉลี่ย", "ระดับคุณภาพ"]
            ];
            PART1_QUESTIONS_DATA.forEach((q, index) => {
                let sum = 0;
                filteredData.forEach(row => sum += row[q.id] || 0);
                const avg = sum / count;
                p1Data.push([index + 1, `${q.title}: ${q.text}`, parseFloat(avg.toFixed(2)), getQualityBadge(avg).text]);
            });
            const wsP1 = XLSX.utils.aoa_to_sheet(p1Data);
            XLSX.utils.book_append_sheet(wb, wsP1, "สถิติ ตอนที่ 1 รายข้อ");

            // Sheet 3: Part 2 Averages
            const p2Data = [
                ["ข้อที่", "หัวข้อรายการและประเด็นเกณฑ์ประเมิน ตอนที่ 2", "ค่าน้ำหนักคะแนนเฉลี่ย", "ระดับคุณภาพ"]
            ];
            PART2_QUESTIONS_DATA.forEach((q, index) => {
                let sum = 0;
                filteredData.forEach(row => sum += row[q.id] || 0);
                const avg = sum / count;
                p2Data.push([index + 1, `${q.title}: ${q.text}`, parseFloat(avg.toFixed(2)), getQualityBadge(avg).text]);
            });
            const wsP2 = XLSX.utils.aoa_to_sheet(p2Data);
            XLSX.utils.book_append_sheet(wb, wsP2, "สถิติ ตอนที่ 2 รายข้อ");

            // Sheet 4: Raw database rows
            const rawHeaders = [
                "ID บันทึก", "ปีการศึกษาที่ประเมิน", "ประทับเวลา", "ชื่อผู้ประเมิน", "ตำแหน่ง/สิทธิ์", "กลุ่มสาระที่สังกัด",
                "วิชาที่ 1 (รหัส)", "วิชาที่ 1 (ชื่อ)", "วิชาที่ 1 (ชั้น)",
                "วิชาที่ 2 (รหัส)", "วิชาที่ 2 (ชื่อ)", "วิชาที่ 2 (ชั้น)",
                "วิชาที่ 3 (รหัส)", "วิชาที่ 3 (ชื่อ)", "วิชาที่ 3 (ชั้น)",
                ...PART1_QUESTIONS_DATA.map(q => q.id), "ข้อเสนอแนะ ตอนที่ 1",
                ...PART2_QUESTIONS_DATA.map(q => q.id), "ข้อเสนอแนะ ตอนที่ 2",
                "ข้อเสนอแนะทั่วไปในอนาคต"
            ];
            const rawDataRows = [rawHeaders];
            filteredData.forEach(row => {
                const vals = [
                    row.id, row.Academic_Year, row.Timestamp, row.Evaluator_Name, row.Position, row.Department,
                    row.Subject1_Code, row.Subject1_Name, row.Subject1_Grade,
                    row.Subject2_Code || "", row.Subject2_Name || "", row.Subject2_Grade || "",
                    row.Subject3_Code || "", row.Subject3_Name || "", row.Subject3_Grade || ""
                ];
                PART1_QUESTIONS_DATA.forEach(q => vals.push(row[q.id]));
                vals.push(row.Suggestions_Part1 || "");
                PART2_QUESTIONS_DATA.forEach(q => vals.push(row[q.id]));
                vals.push(row.Suggestions_Part2 || "");
                vals.push(row.General_Suggestions || "");
                rawDataRows.push(vals);
            });
            const wsRaw = XLSX.utils.aoa_to_sheet(rawDataRows);
            XLSX.utils.book_append_sheet(wb, wsRaw, "ฐานข้อมูลประเมินดิบ");

            // Format column widths for clarity
            wsDash['!cols'] = [{ wch: 45 }, { wch: 30 }];
            wsP1['!cols'] = [{ wch: 8 }, { wch: 85 }, { wch: 22 }, { wch: 22 }];
            wsP2['!cols'] = [{ wch: 8 }, { wch: 85 }, { wch: 22 }, { wch: 22 }];

            XLSX.writeFile(wb, `Curriculum_Report_Year_${selectedYear}.xlsx`);
            showToast(`📁 ดาวน์โหลดรายงานวิเคราะห์ของปี ${selectedYear} สำเร็จ!`);
        }

        function loadPrepopulatedMocks() {
            evaluationDatabase = [
                {
                    id: "rec_mock_1", Academic_Year: "2568",
                    Timestamp: "17/7/2026 08:32:15", Evaluator_Name: "วิทวัส แสนพรม", Position: "ครู", Department: "วิทยาศาสตร์และเทคโนโลยี",
                    Subject1_Code: "ว15101", Subject1_Name: "วิทยาศาสตร์และเทคโนโลยี", Subject1_Grade: "ป.5",
                    Subject2_Code: "ว21101", Subject2_Name: "วิทยาการคำนวณ", Subject2_Grade: "ม.1",
                    Subject3_Code: "", Subject3_Name: "", Subject3_Grade: "",
                    part1_1_1: 4, part1_1_2: 4, part1_1_3: 3, part1_1_4: 4, part1_2_1: 4, part1_2_2: 3, part1_3_0: 4, part1_4_0: 4, part1_5_0: 3,
                    Suggestions_Part1: "การจัดทำส่วนนำหลักสูตรสอดรับกับนโยบายทักษะความรู้ท้องถิ่นร้อยเอ็ดอย่างลงตัว",
                    part2_1_1: 4, part2_1_2: 4, part2_1_3: 3, part2_1_4: 4, part2_1_5: 4, part2_2_1: 4, part2_2_2: 4, part2_2_3: 3, part2_2_4: 4, part2_3_1: 3, part2_3_2: 4, part2_3_3: 4, part2_4_1: 3, part2_4_2: 4, part2_4_3: 4,
                    Suggestions_Part2: "หน่วยเรียนรู้มีลำดับการไหลขององค์ความรู้ดีเยี่ยมและบูรณาการสื่อเชิงเทคโนโลยี",
                    General_Suggestions: "ต้องการพัฒนาคอร์สเสริมทักษะ AI ทางการเรียนรู้สำหรับนักเรียนระดับชั้นสูงต่อไป"
                },
                {
                    id: "rec_mock_2", Academic_Year: "2568",
                    Timestamp: "17/7/2026 09:15:22", Evaluator_Name: "รัชนีกร สร้อยประเสริฐ", Position: "ครู", Department: "คณิตศาสตร์",
                    Subject1_Code: "ค14101", Subject1_Name: "คณิตศาสตร์พื้นฐาน", Subject1_Grade: "ป.4",
                    Subject2_Code: "", Subject2_Name: "", Subject2_Grade: "",
                    Subject3_Code: "", Subject3_Name: "", Subject3_Grade: "",
                    part1_1_1: 3, part1_1_2: 3, part1_1_3: 4, part1_1_4: 3, part1_2_1: 3, part1_2_2: 4, part1_3_0: 3, part1_4_0: 4, part1_5_0: 4,
                    Suggestions_Part1: "",
                    part2_1_1: 3, part2_1_2: 4, part2_1_3: 4, part2_1_4: 3, part2_1_5: 3, part2_2_1: 3, part2_2_2: 3, part2_2_3: 4, part2_2_4: 4, part2_3_1: 4, part2_3_2: 3, part2_3_3: 4, part2_4_1: 4, part2_4_2: 3, part2_4_3: 3,
                    Suggestions_Part2: "จัดกิจกรรมเชิงแก้ปัญหากระตุ้นความกระตือรือร้นของนักเรียนประถมค่อนข้างเห็นภาพชัด",
                    General_Suggestions: "อยากได้รับการสนับสนุนเอกสารคำอธิบายเกณฑ์เปรียบเทียบจากกลุ่มบริหารวิชาการในอนาคต"
                },
                {
                    id: "rec_mock_3", Academic_Year: "2569",
                    Timestamp: "17/7/2026 09:41:00", Evaluator_Name: "รณชัย พลเยี่ยม", Position: "ผู้อำนวยการโรงเรียน", Department: "ภาษาไทย",
                    Subject1_Code: "ท16101", Subject1_Name: "ภาษาไทยหลัก", Subject1_Grade: "ป.6",
                    Subject2_Code: "", Subject2_Name: "", Subject2_Grade: "",
                    Subject3_Code: "", Subject3_Name: "", Subject3_Grade: "",
                    part1_1_1: 4, part1_1_2: 4, part1_1_3: 4, part1_1_4: 4, part1_2_1: 4, part1_2_2: 4, part1_3_0: 4, part1_4_0: 4, part1_5_0: 4,
                    Suggestions_Part1: "หลักสูตรโรงเรียนรัฐประชาวิทยาคารมีความก้าวหน้าเชิงเนื้อหา และปรับปรุงอยู่ตลอดเวลา",
                    part2_1_1: 4, part2_1_2: 4, part2_1_3: 4, part2_1_4: 4, part2_1_5: 4, part2_2_1: 4, part2_2_2: 4, part2_2_3: 4, part2_2_4: 4, part2_3_1: 4, part2_3_2: 4, part2_3_3: 4, part2_4_1: 4, part2_4_2: 4, part2_4_3: 4,
                    Suggestions_Part2: "การนำไปออกแบบหน่วยและปฏิบัติจริงสอดคล้องอย่างเป็นระบบ ครบถ้วน",
                    General_Suggestions: "มุ่งมั่นรณรงค์พัฒนาการนิเทศอย่างสร้างสรรค์เพื่อสิทธิประโยชน์สูงสุดของผู้เรียนอย่างต่อเนื่อง"
                }
            ];
            localStorage.setItem(STORAGE_KEY, JSON.stringify(evaluationDatabase));
        }

        function generateMockData() {
            const mockNames = ["นิรุตติ์ แดนไทย", "กฤษณะ ภูมิใจ", "วไลลักษณ์ ยอดรัก", "ปกรณ์ วงศ์แก้ว", "ศิริวรรณ ชูศรี"];
            const mockPositions = ["ครู", "รองผู้อำนวยการโรงเรียน", "ครู", "ครู", "ครู"];
            const mockDepts = ["ภาษาต่างประเทศ", "สังคมศึกษา ศาสนา และวัฒนธรรม", "ศิลปะ", "สุขศึกษาและพลศึกษา", "การงานอาชีพ"];
            const mockSubs = [
                { code: "อ15101", name: "ภาษาอังกฤษหลัก", grade: "ป.5" },
                { code: "ส13101", name: "สังคมศึกษาและประวัติศาสตร์", grade: "ป.3" },
                { code: "ศ21101", name: "ศิลปะบูรณาการสร้างสรรค์", grade: "ม.1" },
                { code: "พ11101", name: "สุขศึกษาและพลศึกษา", grade: "ป.1" },
                { code: "ง14101", name: "การงานอาชีพเบื้องต้น", grade: "ป.4" }
            ];
            const years = ["2568", "2569", "2570"];

            const extraData = [];
            for (let i = 0; i < 5; i++) {
                const ans = {};
                PART1_QUESTIONS_DATA.forEach(q => ans[q.id] = Math.floor(Math.random() * 2) + 3); // 3 or 4
                PART2_QUESTIONS_DATA.forEach(q => ans[q.id] = Math.floor(Math.random() * 3) + 2); // 2, 3, or 4

                const pickedSub = mockSubs[i];
                const pickedYear = years[Math.floor(Math.random() * years.length)];

                const record = {
                    id: "rec_mock_rand_" + Date.now() + "_" + Math.floor(Math.random() * 1000) + "_" + i,
                    Timestamp: new Date(Date.now() - Math.random() * 50000000).toLocaleString('th-TH'),
                    Academic_Year: pickedYear,
                    Evaluator_Name: mockNames[i],
                    Position: mockPositions[i],
                    Department: mockDepts[i],
                    Subject1_Code: pickedSub.code,
                    Subject1_Name: pickedSub.name,
                    Subject1_Grade: pickedSub.grade,
                    Subject2_Code: "", Subject2_Name: "", Subject2_Grade: "",
                    Subject3_Code: "", Subject3_Name: "", Subject3_Grade: "",
                    ...ans,
                    Suggestions_Part1: `ข้อเสนอแนะตอนที่ 1 พัฒนาอย่างสม่ำเสมอ โดยครู ${mockNames[i]}`,
                    Suggestions_Part2: "จัดเตรียมแผนการเรียนรู้บูรณาการ Active Learning และประเมินผลได้มาตรฐานเชิงรุก",
                    General_Suggestions: "ต้องการสื่อไอทีหรือฮาร์ดแวร์เพื่อช่วยอำนวยความสะดวกในสไลด์และเกมพัฒนาทักษะ"
                };
                extraData.push(record);
            }

            evaluationDatabase = evaluationDatabase.concat(extraData);
            localStorage.setItem(STORAGE_KEY, JSON.stringify(evaluationDatabase));

            showToast("🎉 สุ่มและสร้างข้อมูลทดสอบเพิ่มอีก 5 รายการสำเร็จ (กระจัดกระจายไปตามปีการศึกษา)!");
            updateAdminPanelData();
        }

        function openConfirmModal() {
            const modal = document.getElementById('confirm-modal');
            modal.classList.remove('hidden');
            setTimeout(() => {
                modal.classList.remove('opacity-0');
                modal.querySelector('div').classList.remove('scale-95');
            }, 50);
        }

        function closeConfirmModal() {
            const modal = document.getElementById('confirm-modal');
            modal.classList.add('opacity-0');
            modal.querySelector('div').classList.add('scale-95');
            setTimeout(() => {
                modal.classList.add('hidden');
            }, 300);
        }

        function executeResetSystem() {
            evaluationDatabase = [];
            localStorage.removeItem(STORAGE_KEY);
            closeConfirmModal();
            showToast("🗑️ ล้างฐานข้อมูลการประเมินเรียบร้อยแล้ว", false);
            updateAdminPanelData();
        }

        function confirmDeleteRecord(id) {
            recordToDeleteId = id;
            const record = evaluationDatabase.find(r => r.id === id);
            if (!record) return;
            document.getElementById('delete-target-name').textContent = record.Evaluator_Name;

            const modal = document.getElementById('delete-confirm-modal');
            modal.classList.remove('hidden');
            setTimeout(() => {
                modal.classList.remove('opacity-0');
                modal.querySelector('div').classList.remove('scale-95');
            }, 50);
        }

        function closeDeleteConfirmModal() {
            const modal = document.getElementById('delete-confirm-modal');
            modal.classList.add('opacity-0');
            modal.querySelector('div').classList.add('scale-95');
            setTimeout(() => {
                modal.classList.add('hidden');
            }, 300);
            recordToDeleteId = null;
        }

        function executeDeleteRecord() {
            if (!recordToDeleteId) return;
            evaluationDatabase = evaluationDatabase.filter(r => r.id !== recordToDeleteId);
            localStorage.setItem(STORAGE_KEY, JSON.stringify(evaluationDatabase));
            closeDeleteConfirmModal();
            showToast("🗑️ ลบข้อมูลการประเมินเรียบร้อยแล้ว", false);
            updateAdminPanelData();
        }
    </script>
</body>
</html>
