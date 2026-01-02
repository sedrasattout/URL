# URL
# مشروع كشف التصيد - متطلبات التنفيذ

##  المتطلبات الأساسية

### 1. متطلبات النظام
- **Python**: 3.8 أو أعلى
- **RAM**: 8GB على الأقل (16GB موصى به)
- **Storage**: 5GB مساحة حرة

### 2. تنزيل وتثبيت المكتبات

#### المكتبات الأساسية:
```bash
# إنشاء بيئة افتراضية (اختياري)
python -m venv phishing_env
source phishing_env/bin/activate  # Linux/Mac
# أو
phishing_env\Scripts\activate  # Windows

# تحديث pip
pip install --upgrade pip

# المكتبات الأساسية
pip install pandas==2.0.3
pip install numpy==1.24.3
pip install matplotlib==3.7.1
pip install seaborn==0.12.2
pip install scikit-learn==1.3.0

# مكتبات التعلم الآلي المتقدمة
pip install xgboost==1.7.6
pip install catboost==1.2   
pip install tensorflow==2.13.0 

# المكتبات المتخصصة
pip install tldextract==3.4.4
pip install python-whois==0.9.0
pip install requests==2.31.0
pip install ipaddress==1.0.23
# ================ تثبيت المكتبات في Google Colab ================
!pip install tensorflow
!pip install catboost
!pip install tldextract
!pip install xgboost
!pip install tensorflow.keras
!pip install requests
!pip install python-whois
