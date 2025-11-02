import React, { useState, useEffect, useMemo } from 'react';
import { Upload, FileText, BarChart3, Zap, CircuitBoard, Filter, Wifi, Calculator, BookOpen, Lightbulb } from 'lucide-react';
import { LineChart, Line, XAxis, YAxis, CartesianGrid, Tooltip, Legend, ResponsiveContainer } from 'recharts';

const App = () => {
  const [activeModule, setActiveModule] = useState('home');
  const [uploadedData, setUploadedData] = useState(null);
  const [calculatedData, setCalculatedData] = useState(null);
  const [isProcessing, setIsProcessing] = useState(false);

  // Mock module data based on the PDF
  const modules = [
    { id: 'acara1', title: 'Pengukuran Dasar Elektronika', icon: FileText },
    { id: 'acara2', title: 'Pembuktian Hukum Ohm', icon: Zap },
    { id: 'acara3', title: 'Pembuktian Hukum Kirchoff', icon: CircuitBoard },
    { id: 'acara4', title: 'Pembagi Tegangan dan Arus', icon: Filter },
    { id: 'acara5', title: 'Rangkaian Tapis', icon: Wifi },
    { id: 'acara6', title: 'Rangkaian RLC', icon: BarChart3 },
    { id: 'acara7', title: 'Karakteristik Dioda', icon: Lightbulb },
    { id: 'acara8', title: 'Rangkaian Penyearah', icon: Calculator }
  ];

  // Mock calculation function (simulating AI processing)
  const processUploadedData = (data) => {
    setIsProcessing(true);
    
    // Simulate AI processing delay
    setTimeout(() => {
      // This would be your actual calculation logic
      const mockCalculatedData = {
        module: 'acara6',
        title: 'Rangkaian RLC - Hasil Perhitungan',
        summary: {
          averageCurrent: 24.86,
          averageVoltage: 2.44,
          resonanceFrequency: 550,
          impedance: 98.2
        },
        chartData: [
          { frequency: 100, current: 10.16, voltage: 2.10 },
          { frequency: 200, current: 15.23, voltage: 2.25 },
          { frequency: 300, current: 18.45, voltage: 2.38 },
          { frequency: 400, current: 21.67, voltage: 2.42 },
          { frequency: 500, current: 24.86, voltage: 2.44 },
          { frequency: 600, current: 22.34, voltage: 2.41 },
          { frequency: 700, current: 19.78, voltage: 2.35 },
          { frequency: 800, current: 17.23, voltage: 2.28 },
          { frequency: 900, current: 14.89, voltage: 2.19 },
          { frequency: 1000, current: 12.67, voltage: 2.10 }
        ]
      };
      setCalculatedData(mockCalculatedData);
      setIsProcessing(false);
    }, 2000);
  };

  const handleFileUpload = (event) => {
    const file = event.target.files[0];
    if (file) {
      const reader = new FileReader();
      reader.onload = (e) => {
        try {
          const data = JSON.parse(e.target.result);
          setUploadedData(data);
          processUploadedData(data);
        } catch (error) {
          // Handle CSV or other formats
          setUploadedData({ filename: file.name, size: file.size });
          processUploadedData({ filename: file.name });
        }
      };
      reader.readAsText(file);
    }
  };

  const HomeScreen = () => (
    <div className="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100">
      <div className="container mx-auto px-4 py-12">
        <div className="text-center mb-12">
          <div className="inline-flex items-center justify-center w-20 h-20 bg-indigo-600 rounded-full mb-6">
            <BookOpen className="w-10 h-10 text-white" />
          </div>
          <h1 className="text-4xl md:text-5xl font-bold text-gray-800 mb-4">
            Laboratorium Elektronika Dasar
          </h1>
          <p className="text-xl text-gray-600 max-w-2xl mx-auto">
            Platform AI untuk analisis data praktikum elektronika dasar FMIPA UNSOED
          </p>
        </div>

        <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-6 mb-12">
          {modules.map((module) => {
            const Icon = module.icon;
            return (
              <button
                key={module.id}
                onClick={() => setActiveModule(module.id)}
                className="bg-white rounded-xl p-6 shadow-lg hover:shadow-xl transition-all duration-300 hover:scale-105 border border-gray-100"
              >
                <div className="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-4 mx-auto">
                  <Icon className="w-6 h-6 text-indigo-600" />
                </div>
                <h3 className="font-semibold text-gray-800 text-center">{module.title}</h3>
              </button>
            );
          })}
        </div>

        <div className="bg-white rounded-2xl p-8 shadow-xl max-w-4xl mx-auto">
          <h2 className="text-2xl font-bold text-gray-800 mb-4 text-center">Fitur Utama</h2>
          <div className="grid md:grid-cols-3 gap-6">
            <div className="text-center">
              <div className="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-3">
                <Upload className="w-8 h-8 text-green-600" />
              </div>
              <h3 className="font-semibold text-gray-800 mb-2">Upload Data</h3>
              <p className="text-gray-600 text-sm">Upload file data pengamatan dalam berbagai format</p>
            </div>
            <div className="text-center">
              <div className="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-3">
                <BarChart3 className="w-8 h-8 text-blue-600" />
              </div>
              <h3 className="font-semibold text-gray-800 mb-2">AI Analysis</h3>
              <p className="text-gray-600 text-sm">Analisis otomatis dengan kecerdasan buatan</p>
            </div>
            <div className="text-center">
              <div className="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-3">
                <FileText className="w-8 h-8 text-purple-600" />
              </div>
              <h3 className="font-semibold text-gray-800 mb-2">Laporan Otomatis</h3>
              <p className="text-gray-600 text-sm">Hasil perhitungan dan grafik siap cetak</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  );

  const ModuleScreen = ({ module }) => {
    const currentModule = modules.find(m => m.id === module);
    const Icon = currentModule?.icon || FileText;

    return (
      <div className="min-h-screen bg-gradient-to-br from-indigo-50 to-purple-100">
        <div className="container mx-auto px-4 py-8">
          <button
            onClick={() => setActiveModule('home')}
            className="mb-6 flex items-center text-indigo-600 hover:text-indigo-800 transition-colors"
          >
            <span className="mr-2">←</span> Kembali ke Beranda
          </button>

          <div className="bg-white rounded-2xl shadow-xl p-8 mb-8">
            <div className="flex items-center mb-6">
              <div className="w-14 h-14 bg-indigo-100 rounded-lg flex items-center justify-center mr-4">
                <Icon className="w-7 h-7 text-indigo-600" />
              </div>
              <h1 className="text-3xl font-bold text-gray-800">{currentModule?.title}</h1>
            </div>

            <div className="grid md:grid-cols-2 gap-8">
              <div>
                <h2 className="text-xl font-semibold text-gray-800 mb-4">Upload Data Pengamatan</h2>
                <div className="border-2 border-dashed border-gray-300 rounded-xl p-8 text-center hover:border-indigo-400 transition-colors">
                  <Upload className="w-12 h-12 text-gray-400 mx-auto mb-4" />
                  <p className="text-gray-600 mb-4">Tarik dan lepas file data Anda di sini</p>
                  <label className="bg-indigo-600 text-white px-6 py-2 rounded-lg cursor-pointer hover:bg-indigo-700 transition-colors">
                    Pilih File
                    <input
                      type="file"
                      className="hidden"
                      onChange={handleFileUpload}
                      accept=".csv,.xlsx,.xls,.json,.txt"
                    />
                  </label>
                  <p className="text-sm text-gray-500 mt-2">Format: CSV, Excel, JSON, atau TXT</p>
                </div>
              </div>

              <div>
                <h2 className="text-xl font-semibold text-gray-800 mb-4">Status Proses</h2>
                {isProcessing ? (
                  <div className="bg-yellow-50 border border-yellow-200 rounded-xl p-6">
                    <div className="flex items-center mb-3">
                      <div className="animate-spin rounded-full h-5 w-5 border-b-2 border-yellow-600 mr-3"></div>
                      <span className="font-medium text-yellow-800">Memproses dengan AI...</span>
                    </div>
                    <p className="text-yellow-700 text-sm">Sistem sedang menganalisis data Anda menggunakan algoritma kecerdasan buatan</p>
                  </div>
                ) : uploadedData ? (
                  <div className="bg-green-50 border border-green-200 rounded-xl p-6">
                    <div className="flex items-center mb-2">
                      <div className="w-5 h-5 bg-green-500 rounded-full mr-3"></div>
                      <span className="font-medium text-green-800">Data berhasil diupload</span>
                    </div>
                    <p className="text-green-700 text-sm">File: {uploadedData.filename || 'data_pengamatan.xlsx'}</p>
                  </div>
                ) : (
                  <div className="bg-gray-50 border border-gray-200 rounded-xl p-6">
                    <div className="flex items-center mb-2">
                      <div className="w-5 h-5 bg-gray-400 rounded-full mr-3"></div>
                      <span className="font-medium text-gray-600">Belum ada data</span>
                    </div>
                    <p className="text-gray-500 text-sm">Upload file data pengamatan untuk memulai analisis</p>
                  </div>
                )}
              </div>
            </div>
          </div>

          {calculatedData && (
            <div className="bg-white rounded-2xl shadow-xl p-8">
              <h2 className="text-2xl font-bold text-gray-800 mb-6">Hasil Analisis AI</h2>
              
              <div className="grid md:grid-cols-2 gap-8 mb-8">
                <div>
                  <h3 className="text-lg font-semibold text-gray-800 mb-4">Ringkasan Hasil</h3>
                  <div className="space-y-3">
                    <div className="flex justify-between py-2 border-b border-gray-100">
                      <span className="text-gray-600">Arus Rata-rata:</span>
                      <span className="font-medium">{calculatedData.summary.averageCurrent} mA</span>
                    </div>
                    <div className="flex justify-between py-2 border-b border-gray-100">
                      <span className="text-gray-600">Tegangan Rata-rata:</span>
                      <span className="font-medium">{calculatedData.summary.averageVoltage} V</span>
                    </div>
                    <div className="flex justify-between py-2 border-b border-gray-100">
                      <span className="text-gray-600">Frekuensi Resonansi:</span>
                      <span className="font-medium">{calculatedData.summary.resonanceFrequency} Hz</span>
                    </div>
                    <div className="flex justify-between py-2">
                      <span className="text-gray-600">Impedansi:</span>
                      <span className="font-medium">{calculatedData.summary.impedance} Ω</span>
                    </div>
                  </div>
                </div>

                <div>
                  <h3 className="text-lg font-semibold text-gray-800 mb-4">Grafik Analisis</h3>
                  <div className="h-64">
                    <ResponsiveContainer width="100%" height="100%">
                      <LineChart data={calculatedData.chartData}>
                        <CartesianGrid strokeDasharray="3 3" stroke="#e5e7eb" />
                        <XAxis 
                          dataKey="frequency" 
                          label={{ value: 'Frekuensi (Hz)', position: 'insideBottom', offset: -5 }}
                          stroke="#6b7280"
                        />
                        <YAxis 
                          label={{ value: 'Arus (mA)', angle: -90, position: 'insideLeft' }}
                          stroke="#6b7280"
                        />
                        <Tooltip 
                          contentStyle={{ 
                            backgroundColor: 'white', 
                            border: '1px solid #e5e7eb', 
                            borderRadius: '8px',
                            boxShadow: '0 4px 6px -1px rgba(0, 0, 0, 0.1)'
                          }}
                        />
                        <Legend />
                        <Line 
                          type="monotone" 
                          dataKey="current" 
                          name="Arus (mA)"
                          stroke="#4f46e5" 
                          strokeWidth={2}
                          dot={{ fill: '#4f46e5', strokeWidth: 2, r: 4 }}
                          activeDot={{ r: 6, stroke: '#4f46e5', strokeWidth: 2 }}
                        />
                      </LineChart>
                    </ResponsiveContainer>
                  </div>
                </div>
              </div>

              <div className="text-center">
                <button className="bg-indigo-600 text-white px-8 py-3 rounded-lg hover:bg-indigo-700 transition-colors font-medium">
                  Unduh Laporan Lengkap (PDF)
                </button>
              </div>
            </div>
          )}
        </div>
      </div>
    );
  };

  return (
    <div className="font-sans">
      {activeModule === 'home' ? <HomeScreen /> : <ModuleScreen module={activeModule} />}
    </div>
  );
};

export default App;
