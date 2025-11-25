import React, { useState } from 'react';
import { Target, Sparkles, Heart, Search, MessageCircle, Briefcase, AlertTriangle, CheckCircle2, XCircle, Info, Menu, User, BookOpen, ArrowRight, Users, Zap, Brain, Gamepad2 } from 'lucide-react';

const DiscGuide = () => {
  const [activeType, setActiveType] = useState('D');
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [currentView, setCurrentView] = useState('home'); // 'home' hoặc 'disc'

  // Dữ liệu DISC với màu sắc tối ưu cho Dark Mode
  const discData = {
    D: {
      code: 'D',
      name: 'Dominance - Người Thống Trị',
      color: 'bg-red-600',
      lightColor: 'bg-red-900/30',
      textColor: 'text-red-400',
      borderColor: 'border-red-500/30',
      icon: <Target className="w-8 h-8" />,
      slogan: "Tôi muốn kết quả ngay lập tức!",
      traits: [
        "Quyết đoán, mạnh mẽ, tự tin.",
        "Thích cạnh tranh và chấp nhận rủi ro.",
        "Hướng tới mục tiêu và kết quả.",
        "Thẳng thắn, đôi khi thiếu kiên nhẫn."
      ],
      strengths: ["Giải quyết vấn đề nhanh", "Có tầm nhìn lãnh đạo", "Không ngại khó khăn"],
      weaknesses: ["Dễ nổi nóng", "Hay áp đặt người khác", "Ít lắng nghe chi tiết"],
      communication: {
        do: ["Nói ngắn gọn, đi thẳng vào vấn đề", "Tập trung vào kết quả và giải pháp", "Cho họ quyền quyết định"],
        dont: ["Nói vòng vo, lan man", "Đi sâu vào chi tiết vụn vặt", "Ra lệnh cho họ"]
      },
      careers: "CEO, Quản lý, Doanh nhân, Luật sư, Trưởng phòng kinh doanh."
    },
    I: {
      code: 'I',
      name: 'Influence - Người Ảnh Hưởng',
      color: 'bg-yellow-500',
      lightColor: 'bg-yellow-900/30',
      textColor: 'text-yellow-400',
      borderColor: 'border-yellow-500/30',
      icon: <Sparkles className="w-8 h-8" />,
      slogan: "Hãy cùng làm việc này thật vui nhé!",
      traits: [
        "Nhiệt tình, lạc quan, cởi mở.",
        "Thích giao tiếp và là tâm điểm chú ý.",
        "Sáng tạo, nhiều ý tưởng mới.",
        "Sợ bị bỏ rơi hoặc không được công nhận."
      ],
      strengths: ["Giỏi thuyết phục", "Tạo động lực cho nhóm", "Giải quyết xung đột bằng sự hài hước"],
      weaknesses: ["Thiếu tập trung vào chi tiết", "Làm việc tùy hứng", "Hứa nhiều nhưng hay quên"],
      communication: {
        do: ["Tạo không khí vui vẻ, thân thiện", "Cho họ cơ hội được nói và chia sẻ", "Khen ngợi họ công khai"],
        dont: ["Quá nghiêm túc, khô khan", "Bỏ qua ý kiến của họ", "Bắt họ làm việc lặp lại nhàm chán"]
      },
      careers: "Sales, Marketing, PR, Diễn giả, Hướng dẫn viên, Nghệ thuật."
    },
    S: {
      code: 'S',
      name: 'Steadiness - Người Kiên Định',
      color: 'bg-emerald-600',
      lightColor: 'bg-emerald-900/30',
      textColor: 'text-emerald-400',
      borderColor: 'border-emerald-500/30',
      icon: <Heart className="w-8 h-8" />,
      slogan: "Chúng ta hãy làm cùng nhau và hỗ trợ nhau.",
      traits: [
        "Trầm tĩnh, kiên nhẫn, hòa nhã.",
        "Biết lắng nghe và thấu hiểu.",
        "Thích sự ổn định, ghét xung đột.",
        "Trung thành và tận tụy."
      ],
      strengths: ["Đáng tin cậy", "Làm việc nhóm tuyệt vời", "Giỏi hòa giải mâu thuẫn"],
      weaknesses: ["Sợ thay đổi đột ngột", "Khó nói lời từ chối", "Thiếu quyết đoán khi cần gấp"],
      communication: {
        do: ["Nói chuyện nhẹ nhàng, chân thành", "Cho họ thời gian suy nghĩ", "Quan tâm đến cảm xúc cá nhân"],
        dont: ["Thúc ép quá mức", "Thay đổi kế hoạch liên tục", "Gây áp lực hoặc to tiếng"]
      },
      careers: "Nhân sự (HR), Giáo viên, Y tá, Chăm sóc khách hàng, Tư vấn tâm lý."
    },
    C: {
      code: 'C',
      name: 'Compliance - Người Tuân Thủ',
      color: 'bg-blue-600',
      lightColor: 'bg-blue-900/30',
      textColor: 'text-blue-400',
      borderColor: 'border-blue-500/30',
      icon: <Search className="w-8 h-8" />,
      slogan: "Hãy làm đúng quy trình và chính xác.",
      traits: [
        "Chính xác, logic, chi tiết.",
        "Tuân thủ quy tắc và quy trình.",
        "Thận trọng, tư duy phản biện cao.",
        "Ít bộc lộ cảm xúc ra ngoài."
      ],
      strengths: ["Phân tích dữ liệu tốt", "Làm việc có hệ thống", "Chất lượng công việc cao"],
      weaknesses: ["Cầu toàn quá mức", "Dễ bị sa lầy vào chi tiết", "Khó tính, hay soi xét"],
      communication: {
        do: ["Cung cấp số liệu, bằng chứng cụ thể", "Trình bày logic, có hệ thống", "Tôn trọng quy trình của họ"],
        dont: ["Nói chung chung, cảm tính", "Thúc ép khi chưa có đủ thông tin", "Phê bình sai sót của họ trước đám đông"]
      },
      careers: "Kế toán, Lập trình viên, Kỹ sư, Kiểm toán, Nhà nghiên cứu, Tài chính."
    }
  };

  const activeData = discData[activeType];

  const navigateTo = (view) => {
    setCurrentView(view);
    setIsMenuOpen(false);
    window.scrollTo(0, 0);
  };

  return (
    <div className="min-h-screen bg-slate-950 font-sans text-slate-200 flex flex-col selection:bg-indigo-500 selection:text-white">
      {/* Website Navbar */}
      <nav className="bg-slate-900/80 backdrop-blur-md border-b border-slate-800 sticky top-0 z-50 shadow-lg shadow-black/20">
        <div className="max-w-6xl mx-auto px-4">
          <div className="flex justify-between items-center h-16">
            {/* Logo area */}
            <div className="flex items-center gap-2 cursor-pointer group" onClick={() => navigateTo('home')}>
              <div className="bg-indigo-600 group-hover:bg-indigo-500 transition-colors text-white p-1.5 rounded-lg shadow-[0_0_15px_rgba(79,70,229,0.5)]">
                <Target className="w-6 h-6" />
              </div>
             < a href=" https://nhakjin.github.io/danielmvch/ " target="_blank"> <span className="font-bold text-xl text-white"> Daniel <span className="text-indigo-400"> Mvch </span></span> </a>
           
            </div>

            {/* Desktop Menu */}
            <div className="hidden md:flex items-center gap-8">
              <button 
                onClick={() => navigateTo('home')}
                className={`font-medium transition-colors ${currentView === 'home' ? 'text-indigo-400' : 'text-slate-400 hover:text-white'}`}
              >
                Trang chủ
              </button>
              <button 
                onClick={() => navigateTo('disc')}
                className={`font-medium transition-colors ${currentView === 'disc' ? 'text-indigo-400' : 'text-slate-400 hover:text-white'}`}
              >
                Tra cứu DISC
              </button>
              <button className="text-slate-400 hover:text-white font-medium transition-colors">Về Chúng Tôi</button>
              <button className="bg-indigo-600 text-white px-5 py-2 rounded-full font-medium hover:bg-indigo-500 transition-all shadow-[0_0_20px_rgba(79,70,229,0.3)] hover:shadow-[0_0_30px_rgba(79,70,229,0.5)] text-sm">
                Liên hệ
              </button>
            </div>

            {/* Mobile Menu Button */}
            <button 
              className="md:hidden p-2 text-slate-400 hover:bg-slate-800 rounded-lg transition-colors"
              onClick={() => setIsMenuOpen(!isMenuOpen)}
            >
              <Menu className="w-6 h-6" />
            </button>
          </div>
        </div>
        
        {/* Mobile Menu Dropdown */}
        {isMenuOpen && (
          <div className="md:hidden border-t border-slate-800 bg-slate-900 px-4 py-2 space-y-2 shadow-2xl">
            <button onClick={() => navigateTo('home')} className="block w-full text-left py-3 px-2 text-slate-300 hover:bg-slate-800 rounded font-medium border-b border-slate-800">Trang chủ</button>
            <button onClick={() => navigateTo('disc')} className="block w-full text-left py-3 px-2 text-slate-300 hover:bg-slate-800 rounded font-medium border-b border-slate-800">Tra cứu DISC</button>
          </div>
        )}
      </nav>

      {/* Main Content Area */}
      <main className="flex-grow w-full">
        
        {/* VIEW 1: LANDING PAGE (HOME) */}
        {currentView === 'home' && (
          <div className="animate-fadeIn">
            {/* Hero Section */}
            <div className="bg-slate-900 border-b border-slate-800 relative overflow-hidden">
               {/* Background decoration */}
               <div className="absolute top-0 right-0 w-1/2 h-full bg-gradient-to-l from-indigo-900/20 to-transparent"></div>
               <div className="absolute -bottom-10 -left-10 w-64 h-64 bg-indigo-600/20 rounded-full mix-blend-screen filter blur-3xl opacity-30"></div>
               <div className="absolute top-10 right-10 w-72 h-72 bg-purple-600/20 rounded-full mix-blend-screen filter blur-3xl opacity-30"></div>

              <div className="max-w-6xl mx-auto px-4 py-20 md:py-28 relative z-10">
                <div className="max-w-3xl">
                  <div className="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-indigo-900/50 border border-indigo-700/50 text-indigo-300 text-xs font-bold uppercase tracking-wider mb-6 shadow-[0_0_10px_rgba(79,70,229,0.2)]">
                    <Sparkles className="w-3 h-3" /> Khám phá tiềm năng bản thân
                  </div>
                  <h1 className="text-5xl md:text-7xl font-extrabold text-white mb-6 leading-tight tracking-tight drop-shadow-lg">
                    Thấu hiểu chính mình <br/>
                    <span className="text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-purple-400 filter drop-shadow-[0_0_10px_rgba(129,140,248,0.3)]">Làm chủ giao tiếp</span>
                  </h1>
                  <p className="text-xl text-slate-400 mb-8 leading-relaxed max-w-2xl">
                    DISC là công cụ mạnh mẽ giúp bạn nhận diện phong cách hành vi của bản thân và người khác. Từ đó xây dựng mối quan hệ tốt đẹp và thành công hơn trong sự nghiệp.
                  </p>
                  <div className="flex flex-col sm:flex-row gap-4">
                    <button 
                      onClick={() => navigateTo('disc')}
                      className="inline-flex items-center justify-center gap-2 px-8 py-4 bg-indigo-600 text-white rounded-full font-bold text-lg hover:bg-indigo-500 transition-all shadow-[0_0_20px_rgba(79,70,229,0.4)] hover:shadow-[0_0_30px_rgba(79,70,229,0.6)] hover:-translate-y-1"
                    >
                      Tra cứu ngay <ArrowRight className="w-5 h-5" />
                    </button>
                    <button className="inline-flex items-center justify-center gap-2 px-8 py-4 bg-slate-800 text-slate-200 border border-slate-700 rounded-full font-bold text-lg hover:bg-slate-700 hover:border-slate-600 transition-all">
                      Tìm hiểu thêm
                    </button>
                  </div>
                </div>
              </div>
            </div>

            {/* Features Section */}
            <div className="py-20 bg-slate-950">
              <div className="max-w-6xl mx-auto px-4">
                <div className="text-center mb-16">
                  <h2 className="text-3xl font-bold text-white mb-4">Tại sao bạn cần biết về DISC?</h2>
                  <p className="text-slate-400 max-w-2xl mx-auto">Không chỉ là một bài trắc nghiệm, DISC là tấm bản đồ giúp bạn định hướng cách ứng xử trong mọi tình huống.</p>
                </div>

                <div className="grid md:grid-cols-3 gap-8">
                  <div className="bg-slate-900 p-8 rounded-2xl border border-slate-800 shadow-lg hover:shadow-indigo-900/20 hover:border-indigo-500/30 transition-all group">
                    <div className="w-12 h-12 bg-blue-900/30 text-blue-400 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                      <Brain className="w-6 h-6" />
                    </div>
                    <h3 className="text-xl font-bold text-white mb-3">Thấu hiểu bản thân</h3>
                    <p className="text-slate-400 leading-relaxed">
                      Biết rõ điểm mạnh để phát huy và điểm yếu để khắc phục. Tìm ra môi trường làm việc lý tưởng cho tính cách của bạn.
                    </p>
                  </div>

                  <div className="bg-slate-900 p-8 rounded-2xl border border-slate-800 shadow-lg hover:shadow-green-900/20 hover:border-green-500/30 transition-all group">
                    <div className="w-12 h-12 bg-green-900/30 text-green-400 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                      <Users className="w-6 h-6" />
                    </div>
                    <h3 className="text-xl font-bold text-white mb-3">Đọc vị người khác</h3>
                    <p className="text-slate-400 leading-relaxed">
                      Nắm bắt nhanh chóng phong cách của đối phương chỉ qua vài câu nói. Điều chỉnh cách giao tiếp để tạo thiện cảm ngay lập tức.
                    </p>
                  </div>

                  <div className="bg-slate-900 p-8 rounded-2xl border border-slate-800 shadow-lg hover:shadow-orange-900/20 hover:border-orange-500/30 transition-all group">
                    <div className="w-12 h-12 bg-orange-900/30 text-orange-400 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                      <Zap className="w-6 h-6" />
                    </div>
                    <h3 className="text-xl font-bold text-white mb-3">Tăng tốc sự nghiệp</h3>
                    <p className="text-slate-400 leading-relaxed">
                      Ứng dụng trong bán hàng, lãnh đạo và làm việc nhóm. Giải quyết xung đột hiệu quả và xây dựng đội ngũ vô địch.
                    </p>
                  </div>
                </div>
              </div>
            </div>
            
            {/* CTA Section */}
            <div className="bg-indigo-950 py-20 text-center text-white relative overflow-hidden border-t border-indigo-900">
                <div className="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')] opacity-5"></div>
                {/* Glow effects */}
                <div className="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[500px] h-[500px] bg-indigo-600/20 rounded-full blur-[100px] pointer-events-none"></div>

                <div className="max-w-4xl mx-auto px-4 relative z-10">
                    <h2 className="text-3xl md:text-4xl font-bold mb-6">Sẵn sàng khám phá nhóm tính cách của bạn?</h2>
                    <p className="text-indigo-200 mb-8 text-lg">Truy cập ngay công cụ tra cứu DISC miễn phí và trực quan nhất của chúng tôi.</p>
                    <button 
                      onClick={() => navigateTo('disc')}
                      className="px-10 py-4 bg-white text-indigo-900 rounded-full font-bold text-lg hover:bg-indigo-50 transition-all shadow-[0_0_30px_rgba(255,255,255,0.2)]"
                    >
                      Bắt đầu Tra Cứu
                    </button>
                </div>
            </div>
          </div>
        )}

        {/* VIEW 2: DISC APP (SUB-PAGE) */}
        {currentView === 'disc' && (
          <div className="max-w-4xl mx-auto p-4 py-8 animate-fadeIn">
            <div className="text-center mb-10">
              <div className="inline-flex items-center justify-center p-2 bg-indigo-900/30 border border-indigo-500/30 rounded-full mb-4 px-4">
                 <Gamepad2 className="w-4 h-4 text-indigo-400 mr-2" />
                 <span className="text-xs font-bold text-indigo-300 uppercase tracking-wider">Công cụ Tra Cứu</span>
              </div>
              <h1 className="text-4xl md:text-5xl font-extrabold text-white mb-4 leading-tight">
                Giải Mã <span className="text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-purple-400">Tính Cách</span> Của Bạn
              </h1>
              <p className="text-slate-400 max-w-2xl mx-auto text-lg leading-relaxed">
                Chọn một nhóm màu sắc bên dưới để khám phá đặc điểm tâm lý, điểm mạnh và bí kíp giao tiếp hiệu quả ngay lập tức.
              </p>
            </div>

            {/* Navigation Quadrants */}
            <div className="grid grid-cols-2 gap-4 md:gap-6 mb-12 max-w-lg mx-auto">
              {Object.values(discData).map((item) => (
                <button
                  key={item.code}
                  onClick={() => setActiveType(item.code)}
                  className={`p-6 rounded-2xl border-2 transition-all duration-300 flex flex-col items-center justify-center gap-2 group relative overflow-hidden
                    ${activeType === item.code 
                      ? `${item.lightColor} ${item.borderColor} scale-105 shadow-[0_0_30px_rgba(0,0,0,0.5)] ring-2 ring-offset-2 ring-offset-slate-900 ring-indigo-500 z-10 bg-slate-800` 
                      : 'bg-slate-900 border-slate-800 hover:bg-slate-800 hover:border-indigo-500/50 hover:shadow-lg'
                    }`}
                >
                  <div className={`transition-transform duration-300 ${activeType === item.code ? `${item.textColor} scale-110` : 'text-slate-600 group-hover:text-slate-400 group-hover:scale-110'}`}>
                    {item.icon}
                  </div>
                  <span className={`text-4xl font-black ${activeType === item.code ? item.textColor : 'text-slate-700 group-hover:text-slate-500'}`}>
                    {item.code}
                  </span>
                  <span className="text-xs font-bold text-slate-500 uppercase tracking-wider">{item.name.split(' - ')[1]}</span>
                </button>
              ))}
            </div>

            {/* Detail Content */}
            <div className="bg-slate-900 rounded-3xl shadow-2xl border border-slate-800 overflow-hidden animate-fadeIn transition-all duration-500 relative">
              
              {/* Header Section */}
              <div className={`${activeData.color} p-8 md:p-10 text-white relative overflow-hidden`}>
                 {/* Glassmorphism overlay for header texture */}
                 <div className="absolute inset-0 bg-gradient-to-br from-white/10 to-black/10"></div>
                 
                 <div className="absolute top-0 right-0 p-8 opacity-20 transform translate-x-10 -translate-y-10 mix-blend-overlay">
                    {React.cloneElement(activeData.icon, { className: "w-80 h-80" })}
                 </div>
                 
                 <div className="absolute top-10 left-10 w-2 h-2 bg-white/40 rounded-full blur-[1px]"></div>
                 <div className="absolute bottom-10 right-20 w-4 h-4 bg-white/20 rounded-full blur-[2px]"></div>

                <div className="flex flex-col md:flex-row items-start md:items-center gap-6 relative z-10">
                  <div className="p-4 bg-black/20 rounded-2xl backdrop-blur-md shadow-inner border border-white/10">
                    {React.cloneElement(activeData.icon, { className: "w-12 h-12 text-white drop-shadow-[0_0_10px_rgba(255,255,255,0.5)]" })}
                  </div>
                  <div>
                    <div className="flex items-center gap-3 mb-2">
                      <h2 className="text-3xl font-bold text-white drop-shadow-md">{activeData.name}</h2>
                      <span className="bg-black/30 px-3 py-1 rounded-full text-xs font-bold uppercase tracking-wider backdrop-blur-sm border border-white/20 text-white/90">
                        Nhóm {activeData.code}
                      </span>
                    </div>
                    <p className="opacity-90 italic text-xl font-light text-white/90">"{activeData.slogan}"</p>
                  </div>
                </div>
              </div>

              <div className="p-8 md:p-10">
                {/* Traits Grid */}
                <div className="grid md:grid-cols-2 gap-12 mb-10">
                  <div>
                    <h3 className="text-lg font-bold mb-6 flex items-center gap-2 text-indigo-400 uppercase tracking-wide border-b border-slate-800 pb-3">
                      <Search className="w-5 h-5" /> Đặc điểm nhận dạng
                    </h3>
                    <ul className="space-y-4">
                      {activeData.traits.map((trait, idx) => (
                        <li key={idx} className="flex items-start gap-4 text-slate-300 bg-slate-800/50 p-4 rounded-2xl border border-slate-700/50 hover:border-indigo-500/30 hover:bg-slate-800 transition-all duration-300">
                          <span className={`w-2 h-2 mt-2.5 rounded-full flex-shrink-0 ${activeData.color} shadow-[0_0_8px_currentColor]`}></span>
                          <span className="leading-relaxed font-medium">{trait}</span>
                        </li>
                      ))}
                    </ul>
                  </div>

                  <div className="space-y-8">
                     {/* Strengths & Weaknesses */}
                    <div>
                      <h3 className="text-lg font-bold mb-5 text-emerald-400 flex items-center gap-2 uppercase tracking-wide border-b border-emerald-900/30 pb-3">
                        <CheckCircle2 className="w-5 h-5" /> Thế mạnh nổi bật
                      </h3>
                      <div className="flex flex-wrap gap-3">
                        {activeData.strengths.map((s, i) => (
                          <span key={i} className="px-4 py-2 bg-emerald-900/20 text-emerald-300 font-bold text-sm rounded-xl border border-emerald-500/20 shadow-sm hover:shadow-emerald-500/10 transition-shadow cursor-default">
                            {s}
                          </span>
                        ))}
                      </div>
                    </div>
                    
                    <div>
                      <h3 className="text-lg font-bold mb-5 text-rose-400 flex items-center gap-2 uppercase tracking-wide border-b border-rose-900/30 pb-3">
                        <AlertTriangle className="w-5 h-5" /> Điểm yếu cần khắc phục
                      </h3>
                      <div className="flex flex-wrap gap-3">
                        {activeData.weaknesses.map((w, i) => (
                          <span key={i} className="px-4 py-2 bg-rose-900/20 text-rose-300 font-bold text-sm rounded-xl border border-rose-500/20 shadow-sm hover:shadow-rose-500/10 transition-shadow cursor-default">
                            {w}
                          </span>
                        ))}
                      </div>
                    </div>
                  </div>
                </div>

                <div className="h-px bg-slate-800 my-10"></div>

                {/* Communication Guide */}
                <div className="mb-10">
                  <h3 className="text-xl font-bold mb-8 flex items-center justify-center gap-3 text-white uppercase tracking-wide">
                    <MessageCircle className="w-6 h-6 text-indigo-400" /> Bí kíp giao tiếp hiệu quả
                  </h3>
                  <div className="grid md:grid-cols-2 gap-8">
                    <div className="bg-emerald-950/20 border border-emerald-900/50 p-8 rounded-3xl hover:bg-emerald-900/20 transition-colors duration-300">
                      <h4 className="font-bold text-emerald-400 mb-6 flex items-center gap-3 text-lg border-b border-emerald-900/50 pb-3">
                        <div className="p-1.5 bg-emerald-900/50 rounded-lg text-emerald-400"><CheckCircle2 className="w-5 h-5" /></div>
                        NÊN LÀM
                      </h4>
                      <ul className="space-y-4">
                        {activeData.communication.do.map((item, idx) => (
                          <li key={idx} className="text-slate-300 flex items-start gap-3">
                            <span className="text-emerald-500 font-bold mt-0.5 text-lg">•</span> 
                            <span className="font-medium">{item}</span>
                          </li>
                        ))}
                      </ul>
                    </div>
                    <div className="bg-rose-950/20 border border-rose-900/50 p-8 rounded-3xl hover:bg-rose-900/20 transition-colors duration-300">
                      <h4 className="font-bold text-rose-400 mb-6 flex items-center gap-3 text-lg border-b border-rose-900/50 pb-3">
                        <div className="p-1.5 bg-rose-900/50 rounded-lg text-rose-400"><XCircle className="w-5 h-5" /></div>
                        HÃY TRÁNH
                      </h4>
                      <ul className="space-y-4">
                        {activeData.communication.dont.map((item, idx) => (
                          <li key={idx} className="text-slate-300 flex items-start gap-3">
                            <span className="text-rose-500 font-bold mt-0.5 text-lg">•</span> 
                            <span className="font-medium">{item}</span>
                          </li>
                        ))}
                      </ul>
                    </div>
                  </div>
                </div>

                 {/* Careers */}
                 <div className="bg-gradient-to-r from-indigo-900/20 to-blue-900/20 p-8 rounded-3xl border border-indigo-500/20 flex flex-col md:flex-row items-start md:items-center gap-6 shadow-lg">
                    <div className="p-4 bg-slate-800 rounded-2xl shadow-lg text-indigo-400 border border-slate-700">
                       <Briefcase className="w-8 h-8" />
                    </div>
                    <div>
                       <h3 className="text-sm font-bold text-indigo-300 uppercase tracking-wider mb-2 flex items-center gap-2">
                         <User className="w-4 h-4" /> Định hướng sự nghiệp
                       </h3>
                       <p className="text-white leading-relaxed font-semibold text-lg">{activeData.careers}</p>
                    </div>
                 </div>
              </div>
            </div>
            
            <div className="mt-8 text-center">
               <button onClick={() => navigateTo('home')} className="text-indigo-400 font-medium hover:text-white transition-colors">
                  &larr; Quay lại Trang chủ
               </button>
            </div>
          </div>
        )}
      </main>
      
      {/* Footer */}
      <footer className="bg-slate-900 border-t border-slate-800 mt-auto py-10">
        <div className="max-w-6xl mx-auto px-4 text-center">
          <div className="flex justify-center items-center gap-2 mb-4">
            <BookOpen className="w-5 h-5 text-indigo-400" />
            <span className="font-bold text-slate-200">DISC Knowledge Hub</span>
          </div>
          <p className="text-slate-500 text-sm mb-4">
            Ứng dụng giúp thấu hiểu hành vi và phát triển bản thân. Nội dung được tổng hợp từ lý thuyết DISC của William Moulton Marston.
          </p>
          <div className="flex justify-center gap-4 text-sm text-slate-500">
             <button onClick={() => navigateTo('home')} className="hover:text-indigo-400 transition-colors">Trang chủ</button>
             <span>•</span>
             <button onClick={() => navigateTo('disc')} className="hover:text-indigo-400 transition-colors">Tra cứu DISC</button>
          </div>
          <p className="text-slate-600 text-xs mt-4">© 2024 DISC Profile Viewer. All rights reserved.</p>
        </div>
      </footer>
    </div>
  );
};

export default DiscGuide;
