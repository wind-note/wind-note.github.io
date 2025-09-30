import React, { useState, useEffect } from 'react';
import { Music, Users, Calendar, Mail, MapPin, Phone, Camera, Play, ArrowRight, Star } from 'lucide-react';

const App = () => {
  const [activeSection, setActiveSection] = useState('home');
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [currentImageIndex, setCurrentImageIndex] = useState(0);

  const galleryImages = [
    'https://placehold.co/400x300/4f46e5/ffffff?text=Wind+Note+Live+1',
    'https://placehold.co/400x300/7c3aed/ffffff?text=Wind+Note+Live+2',
    'https://placehold.co/400x300/2563eb/ffffff?text=Wind+Note+Rehearsal',
    'https://placehold.co/400x300/dc2626/ffffff?text=Wind+Note+Studio',
    'https://placehold.co/400x300/059669/ffffff?text=Wind+Note+Event',
    'https://placehold.co/400x300/d97706/ffffff?text=Wind+Note+Group'
  ];

  const members = [
    {
      name: "张小明",
      role: "主唱",
      instrument: "Vocal",
      image: "https://placehold.co/200x200/6366f1/ffffff?text=张小明",
      description: "蓬莱二中高二学生，拥有清澈的嗓音和出色的舞台表现力"
    },
    {
      name: "李小红",
      role: "吉他手",
      instrument: "Guitar",
      image: "https://placehold.co/200x200/8b5cf6/ffffff?text=李小红",
      description: "音乐天才，擅长多种吉他演奏技巧"
    },
    {
      name: "王小刚",
      role: "贝斯手",
      instrument: "Bass",
      image: "https://placehold.co/200x200/06b6d4/ffffff?text=王小刚",
      description: "节奏感极强，为乐队提供稳定的低音基础"
    },
    {
      name: "赵小美",
      role: "键盘手",
      instrument: "Keyboard",
      image: "https://placehold.co/200x200/10b981/ffffff?text=赵小美",
      description: "多才多艺，擅长多种乐器和音乐制作"
    },
    {
      name: "孙小强",
      role: "鼓手",
      instrument: "Drums",
      image: "https://placehold.co/200x200/f59e0b/ffffff?text=孙小强",
      description: "节奏掌控者，为乐队注入强劲的节拍动力"
    }
  ];

  const events = [
    {
      date: "2024-01-15",
      title: "校园音乐节演出",
      location: "蓬莱二中大礼堂",
      description: "首次公开演出，展示原创作品"
    },
    {
      date: "2024-02-20",
      title: "音乐节参赛",
      location: "市青少年活动中心",
      description: "参加全市中学生音乐节比赛"
    },
    {
      date: "2024-03-10",
      title: "慈善义演",
      location: "市中心广场",
      description: "为贫困学生筹集学习用品"
    }
  ];

  useEffect(() => {
    const interval = setInterval(() => {
      setCurrentImageIndex((prev) => (prev + 1) % galleryImages.length);
    }, 3000);
    return () => clearInterval(interval);
  }, []);

  const scrollToSection = (sectionId) => {
    setActiveSection(sectionId);
    setIsMenuOpen(false);
    document.getElementById(sectionId)?.scrollIntoView({ behavior: 'smooth' });
  };

  return (
    <div className="min-h-screen bg-gradient-to-br from-slate-900 via-purple-900 to-slate-900">
      {/* Navigation */}
      <nav className="fixed top-0 w-full bg-black/20 backdrop-blur-md z-50 border-b border-white/10">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex justify-between items-center py-4">
            <div className="flex items-center space-x-2">
              <Music className="h-8 w-8 text-purple-400" />
              <span className="text-2xl font-bold text-white">Wind-Note</span>
            </div>
            
            <div className="hidden md:flex space-x-8">
              {['home', 'about', 'members', 'events', 'gallery', 'contact'].map((item) => (
                <button
                  key={item}
                  onClick={() => scrollToSection(item)}
                  className={`capitalize text-sm font-medium transition-colors ${
                    activeSection === item ? 'text-purple-400' : 'text-gray-300 hover:text-white'
                  }`}
                >
                  {item === 'home' ? '首页' : item === 'about' ? '关于' : item === 'members' ? '成员' : item === 'events' ? '演出' : item === 'gallery' ? '相册' : '联系'}
                </button>
              ))}
            </div>

            <button
              className="md:hidden text-white"
              onClick={() => setIsMenuOpen(!isMenuOpen)}
            >
              <div className="w-6 h-6 flex flex-col justify-center space-y-1">
                <div className="w-full h-0.5 bg-white"></div>
                <div className="w-full h-0.5 bg-white"></div>
                <div className="w-full h-0.5 bg-white"></div>
              </div>
            </button>
          </div>

          {isMenuOpen && (
            <div className="md:hidden py-4 border-t border-white/10">
              {['home', 'about', 'members', 'events', 'gallery', 'contact'].map((item) => (
                <button
                  key={item}
                  onClick={() => scrollToSection(item)}
                  className="block w-full text-left py-2 capitalize text-gray-300 hover:text-white"
                >
                  {item === 'home' ? '首页' : item === 'about' ? '关于' : item === 'members' ? '成员' : item === 'events' ? '演出' : item === 'gallery' ? '相册' : '联系'}
                </button>
              ))}
            </div>
          )}
        </div>
      </nav>

      {/* Hero Section */}
      <section id="home" className="pt-20 min-h-screen flex items-center">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
          <div className="grid lg:grid-cols-2 gap-12 items-center">
            <div className="space-y-8">
              <div className="space-y-4">
                <h1 className="text-5xl lg:text-7xl font-bold text-white">
                  Wind-
                  <span className="text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-pink-400">
                    Note
                  </span>
                </h1>
                <p className="text-xl text-gray-300 leading-relaxed">
                  蓬莱二中学生乐队，用音乐编织青春的梦想，让每一个音符都承载着我们的热情与才华
                </p>
              </div>
              
              <div className="flex flex-col sm:flex-row gap-4">
                <button 
                  onClick={() => scrollToSection('about')}
                  className="bg-gradient-to-r from-purple-600 to-pink-600 text-white px-8 py-4 rounded-full font-semibold hover:from-purple-700 hover:to-pink-700 transition-all duration-300 flex items-center justify-center space-x-2"
                >
                  <span>了解更多</span>
                  <ArrowRight className="h-5 w-5" />
                </button>
                <button 
                  onClick={() => scrollToSection('events')}
                  className="border-2 border-purple-400 text-purple-400 px-8 py-4 rounded-full font-semibold hover:bg-purple-400 hover:text-white transition-all duration-300"
                >
                  查看演出
                </button>
              </div>

              <div className="flex items-center space-x-8 pt-8">
                <div className="text-center">
                  <div className="text-3xl font-bold text-white">5</div>
                  <div className="text-gray-400 text-sm">成员</div>
                </div>
                <div className="text-center">
                  <div className="text-3xl font-bold text-white">10+</div>
                  <div className="text-gray-400 text-sm">演出</div>
                </div>
                <div className="text-center">
                  <div className="text-3xl font-bold text-white">20+</div>
                  <div className="text-gray-400 text-sm">作品</div>
                </div>
              </div>
            </div>

            <div className="relative">
              <div className="relative w-full h-96 lg:h-[500px] rounded-2xl overflow-hidden">
                <img
                  src={galleryImages[currentImageIndex]}
                  alt="Wind-Note Band"
                  className="w-full h-full object-cover transition-opacity duration-1000"
                />
                <div className="absolute inset-0 bg-gradient-to-t from-black/50 to-transparent"></div>
                <div className="absolute bottom-6 left-6 right-6">
                  <h3 className="text-white text-2xl font-bold mb-2">Wind-Note 乐队</h3>
                  <p className="text-gray-200">用音乐诠释青春，用热情点燃梦想</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* About Section */}
      <section id="about" className="py-20 bg-black/20">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold text-white mb-4">关于我们</h2>
            <p className="text-xl text-gray-300 max-w-3xl mx-auto">
              Wind-Note 是一支由蓬莱二中学生组成的乐队，我们致力于创作和演奏充满青春活力的音乐作品
            </p>
          </div>

          <div className="grid md:grid-cols-2 gap-12 items-center">
            <div className="space-y-6">
              <div className="bg-white/5 backdrop-blur-sm rounded-2xl p-8 border border-white/10">
                <h3 className="text-2xl font-bold text-white mb-4 flex items-center">
                  <Star className="h-6 w-6 text-yellow-400 mr-2" />
                  我们的理念
                </h3>
                <p className="text-gray-300 leading-relaxed">
                  我们相信音乐是青春最美好的表达方式。Wind-Note 致力于将校园生活的美好瞬间转化为动人的旋律，
                  用音乐传递正能量，激励更多的同学追求自己的梦想。
                </p>
              </div>

              <div className="bg-white/5 backdrop-blur-sm rounded-2xl p-8 border border-white/10">
                <h3 className="text-2xl font-bold text-white mb-4 flex items-center">
                  <Music className="h-6 w-6 text-purple-400 mr-2" />
                  音乐风格
                </h3>
                <p className="text-gray-300 leading-relaxed">
                  我们的音乐风格融合了流行、摇滚和民谣元素，既有青春的活力，也有深沉的情感表达。
                  每一首作品都承载着我们对生活的感悟和对未来的憧憬。
                </p>
              </div>
            </div>

            <div className="space-y-6">
              <img
                src="https://placehold.co/600x400/6366f1/ffffff?text=Wind+Note+Studio"
                alt="Rehearsal Studio"
                className="rounded-2xl w-full h-80 object-cover"
              />
              <div className="grid grid-cols-2 gap-4">
                <img
                  src="https://placehold.co/300x200/8b5cf6/ffffff?text=Music+1"
                  alt="Music Creation"
                  className="rounded-xl w-full h-32 object-cover"
                />
                <img
                  src="https://placehold.co/300x200/06b6d4/ffffff?text=Music+2"
                  alt="Performance"
                  className="rounded-xl w-full h-32 object-cover"
                />
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Members Section */}
      <section id="members" className="py-20">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold text-white mb-4">乐队成员</h2>
            <p className="text-xl text-gray-300">才华横溢的蓬莱二中学子，共同创造美妙音乐</p>
          </div>

          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            {members.map((member, index) => (
              <div key={index} className="bg-white/5 backdrop-blur-sm rounded-2xl p-6 border border-white/10 hover:bg-white/10 transition-all duration-300">
                <div className="text-center">
                  <img
                    src={member.image}
                    alt={member.name}
                    className="w-32 h-32 rounded-full mx-auto mb-4 object-cover"
                  />
                  <h3 className="text-xl font-bold text-white mb-2">{member.name}</h3>
                  <p className="text-purple-400 font-semibold mb-1">{member.role}</p>
                  <p className="text-gray-400 text-sm mb-3">{member.instrument}</p>
                  <p className="text-gray-300 text-sm">{member.description}</p>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Events Section */}
      <section id="events" className="py-20 bg-black/20">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold text-white mb-4">演出安排</h2>
            <p className="text-xl text-gray-300">关注我们的演出活动，一起感受音乐的魅力</p>
          </div>

          <div className="space-y-6">
            {events.map((event, index) => (
              <div key={index} className="bg-white/5 backdrop-blur-sm rounded-2xl p-6 border border-white/10 hover:bg-white/10 transition-all duration-300">
                <div className="flex flex-col md:flex-row md:items-center justify-between">
                  <div className="flex-1">
                    <div className="flex items-center space-x-4 mb-2">
                      <div className="text-2xl font-bold text-purple-400">
                        {new Date(event.date).toLocaleDateString('zh-CN', { 
                          year: 'numeric', 
                          month: 'long', 
                          day: 'numeric' 
                        })}
                      </div>
                      <div className="text-white font-semibold text-xl">{event.title}</div>
                    </div>
                    <div className="flex items-center space-x-2 text-gray-300">
                      <MapPin className="h-4 w-4" />
                      <span>{event.location}</span>
                    </div>
                    <p className="text-gray-400 mt-2">{event.description}</p>
                  </div>
                  <button className="mt-4 md:mt-0 bg-gradient-to-r from-purple-600 to-pink-600 text-white px-6 py-2 rounded-full font-semibold hover:from-purple-700 hover:to-pink-700 transition-all duration-300">
                    了解详情
                  </button>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Gallery Section */}
      <section id="gallery" className="py-20">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold text-white mb-4">相册</h2>
            <p className="text-xl text-gray-300">记录我们的音乐旅程和美好时光</p>
          </div>

          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            {galleryImages.map((image, index) => (
              <div key={index} className="group relative overflow-hidden rounded-2xl aspect-square">
                <img
                  src={image}
                  alt={`Gallery ${index + 1}`}
                  className="w-full h-full object-cover transition-transform duration-300 group-hover:scale-110"
                />
                <div className="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                  <div className="absolute bottom-4 left-4 right-4">
                    <Camera className="h-6 w-6 text-white mx-auto mb-2" />
                    <p className="text-white text-center">相册 {index + 1}</p>
                  </div>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section id="contact" className="py-20 bg-black/20">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold text-white mb-4">联系我们</h2>
            <p className="text-xl text-gray-300">想了解更多关于我们的信息？欢迎随时联系我们</p>
          </div>

          <div className="grid md:grid-cols-2 gap-12">
            <div className="space-y-8">
              <div className="flex items-center space-x-4">
                <div className="bg-purple-600 p-3 rounded-full">
                  <Mail className="h-6 w-6 text-white" />
                </div>
                <div>
                  <h3 className="text-white font-semibold">邮箱</h3>
                  <p className="text-gray-400">windnote@penglai2.edu.cn</p>
                </div>
              </div>
              
              <div className="flex items-center space-x-4">
                <div className="bg-purple-600 p-3 rounded-full">
                  <Phone className="h-6 w-6 text-white" />
                </div>
                <div>
                  <h3 className="text-white font-semibold">电话</h3>
                  <p className="text-gray-400">138-0000-0000</p>
                </div>
              </div>
              
              <div className="flex items-center space-x-4">
                <div className="bg-purple-600 p-3 rounded-full">
                  <MapPin className="h-6 w-6 text-white" />
                </div>
                <div>
                  <h3 className="text-white font-semibold">地址</h3>
                  <p className="text-gray-400">山东省烟台市蓬莱区蓬莱二中音乐楼</p>
                </div>
              </div>
            </div>

            <div className="bg-white/5 backdrop-blur-sm rounded-2xl p-8 border border-white/10">
              <h3 className="text-2xl font-bold text-white mb-6">发送消息</h3>
              <form className="space-y-4">
                <div>
                  <input
                    type="text"
                    placeholder="您的姓名"
                    className="w-full bg-white/10 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:outline-none focus:border-purple-400 transition-colors"
                  />
                </div>
                <div>
                  <input
                    type="email"
                    placeholder="您的邮箱"
                    className="w-full bg-white/10 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:outline-none focus:border-purple-400 transition-colors"
                  />
                </div>
                <div>
                  <textarea
                    rows="4"
                    placeholder="您的消息"
                    className="w-full bg-white/10 border border-white/20 rounded-lg px-4 py-3 text-white placeholder-gray-400 focus:outline-none focus:border-purple-400 transition-colors resize-none"
                  ></textarea>
                </div>
                <button
                  type="submit"
                  className="w-full bg-gradient-to-r from-purple-600 to-pink-600 text-white py-3 rounded-lg font-semibold hover:from-purple-700 hover:to-pink-700 transition-all duration-300"
                >
                  发送消息
                </button>
              </form>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-black/40 py-12 border-t border-white/10">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="text-center">
            <div className="flex items-center justify-center space-x-2 mb-4">
              <Music className="h-8 w-8 text-purple-400" />
              <span className="text-2xl font-bold text-white">Wind-Note</span>
            </div>
            <p className="text-gray-400 mb-4">
              蓬莱二中学生乐队 - 用音乐编织青春的梦想
            </p>
            <p className="text-gray-500 text-sm">
              © 2024 Wind-Note Band. All rights reserved.
            </p>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default App;
