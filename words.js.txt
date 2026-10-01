// Dữ liệu mẫu HSK 1-3 (Bạn sẽ học cách thêm phần còn lại sau)
const hskData = {
    hsk1: [
        {hanzi: "我", pinyin: "wǒ", vie: "Tôi, tao", type: "Đại từ"},
        {hanzi: "你", pinyin: "nǐ", vie: "Bạn, anh", type: "Đại từ"},
        {hanzi: "好", pinyin: "hǎo", vie: "Tốt, đẹp, khỏe", type: "Tính/Động từ"},
        {hanzi: "吃", pinyin: "chī", vie: "Ăn", type: "Động từ"},
        {hanzi: "喝", pinyin: "hē", vie: "Uống", type: "Động từ"}
    ],
    hsk2: [
        {hanzi: "学习", pinyin: "xué xí", vie: "Học tập", type: "Động từ"},
        {hanzi: "工作", pinyin: "gōng zuò", vie: "Công việc/Làm việc", type: "Danh/Động từ"},
        {hanzi: "医生", pinyin: "yī shēng", vie: "Bác sĩ", type: "Danh từ"},
        {hanzi: "喜欢", pinyin: "xǐ huan", vie: "Thích", type: "Động từ"}
    ],
    hsk3: [
        {hanzi: "问题", pinyin: "wèn tí", vie: "Vấn đề/Câu hỏi", type: "Danh từ"},
        {hanzi: "准备", pinyin: "zhǔn bèi", vie: "Chuẩn bị", type: "Động từ"},
        {hanzi: "介绍", pinyin: "jiè shào", vie: "Giới thiệu", type: "Động từ"},
        {hanzi: "虽然...但是", pinyin: "suī rán... dàn shì", vie: "Tuy nhiên... nhưng", type: "Liên từ"}
    ]
};

const grammarData = [
    {level: "HSK 1", title: "Cấu trúc câu cơ bản: S + V + O", explain: "Chủ ngữ + Động từ + Tân ngữ.", examples: [ {zh: "我吃饭。", vi: "Tôi ăn cơm."} ]},
    {level: "HSK 1", title: "Trợ từ nghi vấn 吗 (ma)", explain: "Dùng ở cuối câu trần thuật để tạo thành câu hỏi Yes/No.", examples: [ {zh: "你好吗？", vi: "Bạn khỏe không?"} ]},
    {level: "HSK 2", title: "Động từ năng nguyện 会 (huì)", explain: "Biểu thị kỹ năng (học mà biết) hoặc khả năng xảy ra.", examples: [ {zh: "我会说汉语。", vi: "Tôi biết nói tiếng Trung."} ]},
    {level: "HSK 3", title: "Câu chữ 被 (bèi)", explain: "Dùng để biểu thị câu bị động (A bị B làm sao đó).", examples: [ {zh: "作业被狗吃了。", vi: "Bài tập bị chó ăn mất rồi."} ]}
];

const quizData = [
    { q: "请问，'你'是什么意思？", a: ["Tôi", "Bạn", "Khỏe", "Ăn"], correct: 1 },
    { q: "Chọn Pinyin đúng cho từ '学习':", a: ["gōng zuò", "xué xí", "yī shēng", "wǒ"], correct: 1 },
    { q: "Điền vào chỗ trống: 我___医生。(Tôi là bác sĩ)", a: ["是", "吃", "喝", "叫"], correct: 0 }
];
