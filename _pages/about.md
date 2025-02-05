import React, { useState } from 'react';
import { Github, Linkedin, Mail, Book, Award } from 'lucide-react';

const EnhancedWebsite = () => {
  const [currentPublication, setCurrentPublication] = useState(0);
  const publications = [
    {
      title: "SwitchTab: Switched Autoencoders Are Effective Tabular Learners",
      authors: "Jing Wu*, Suiyao Chen*, Qi Zhao, et al.",
      venue: "AAAI 2024",
      image: "images/Switch.png",
      paper: "https://arxiv.org/pdf/2401.02013",
    },
    // Add other publications here
  ];

  return (
    <div className="max-w-6xl mx-auto p-6">
      {/* Header Enhancement */}
      <div className="text-center mb-8">
        <h1 className="text-4xl font-bold mb-4">Jing Wu</h1>
        <p className="text-xl text-gray-600 mb-4">Applied Research Scientist @ AWS, Amazon</p>
        <div className="flex justify-center gap-4 mb-6">
          <a href="mailto:your.email@example.com" className="inline-flex items-center gap-2 px-4 py-2 bg-blue-600 text-white rounded hover:bg-blue-700">
            <Mail size={18} />
            Contact
          </a>
          <a href="https://github.com/yourusername" className="inline-flex items-center gap-2 px-4 py-2 border border-gray-300 rounded hover:bg-gray-50">
            <Github size={18} />
            GitHub
          </a>
          <a href="https://linkedin.com/in/yourusername" className="inline-flex items-center gap-2 px-4 py-2 border border-gray-300 rounded hover:bg-gray-50">
            <Linkedin size={18} />
            LinkedIn
          </a>
        </div>
        <div className="bg-blue-50 p-4 rounded-lg inline-block">
          <p className="text-blue-800">⭐ Open to opportunities and collaborations ⭐</p>
        </div>
      </div>

      {/* Research Interests Enhancement */}
      <div className="mb-8">
        <h2 className="text-2xl font-bold mb-4 flex items-center gap-2">
          <Book className="text-blue-600" size={24} />
          Research Interests
        </h2>
        <div className="grid md:grid-cols-2 gap-6">
          <div className="bg-gray-50 p-6 rounded-lg">
            <h3 className="font-semibold mb-2">Core Research Areas</h3>
            <ul className="space-y-2">
              <li className="flex items-center gap-2">
                <span className="w-2 h-2 bg-blue-600 rounded-full"></span>
                Large Language Models (LLM)
              </li>
              <li className="flex items-center gap-2">
                <span className="w-2 h-2 bg-blue-600 rounded-full"></span>
                Computer Vision
              </li>
              <li className="flex items-center gap-2">
                <span className="w-2 h-2 bg-blue-600 rounded-full"></span>
                Multi-modality Learning
              </li>
            </ul>
          </div>
          <div className="bg-gray-50 p-6 rounded-lg">
            <h3 className="font-semibold mb-2">Application Domains</h3>
            <ul className="space-y-2">
              <li className="flex items-center gap-2">
                <span className="w-2 h-2 bg-green-600 rounded-full"></span>
                Remote Sensing
              </li>
              <li className="flex items-center gap-2">
                <span className="w-2 h-2 bg-green-600 rounded-full"></span>
                Robotics
              </li>
              <li className="flex items-center gap-2">
                <span className="w-2 h-2 bg-green-600 rounded-full"></span>
                Sustainable Agriculture
              </li>
            </ul>
          </div>
        </div>
      </div>

      {/* Enhanced News Section */}
      <div className="news-container mb-8">
        <h2 className="text-2xl font-bold mb-4">📰 News & Updates</h2>
        <div className="news-updates bg-white border border-gray-200 rounded-lg">
          <div className="p-4 space-y-4">
            {/* Existing news items with enhanced styling */}
            <div className="border-l-4 border-blue-600 pl-4">
              <div className="text-sm text-gray-500">January 2025</div>
              <div className="font-semibold">Paper Accepted at AAAI</div>
              <div className="text-gray-600">Improving Model Probability Calibration by Integration of Large Data Sources with Biased Labels</div>
            </div>
            {/* Add more news items with the same styling */}
          </div>
        </div>
      </div>

      {/* Enhanced Publications Section */}
      <div className="mb-8">
        <h2 className="text-2xl font-bold mb-4">📑 Selected Publications</h2>
        <div className="bg-gray-50 p-6 rounded-lg">
          <div className="publication-grid grid md:grid-cols-3 gap-6">
            {publications.map((pub, index) => (
              <div 
                key={index}
                className="publication-card border border-gray-200 rounded-lg overflow-hidden hover:shadow-lg transition-shadow"
              >
                <img 
                  src={pub.image} 
                  alt={pub.title}
                  className="w-full h-48 object-cover"
                />
                <div className="p-4">
                  <h3 className="font-semibold text-lg mb-2">{pub.title}</h3>
                  <p className="text-gray-600 text-sm mb-2">{pub.authors}</p>
                  <p className="text-blue-600 text-sm mb-4">{pub.venue}</p>
                  <a 
                    href={pub.paper}
                    className="text-blue-600 hover:underline text-sm"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    Read the paper →
                  </a>
                </div>
              </div>
            ))}
          </div>
        </div>
      </div>

      <style jsx global>{`
        .news-updates {
          max-height: 400px;
          overflow-y: auto;
        }
        
        .publication-card {
          background: white;
          transition: transform 0.2s;
        }
        
        .publication-card:hover {
          transform: translateY(-4px);
        }
      `}</style>
    </div>
  );
};

export default EnhancedWebsite;
