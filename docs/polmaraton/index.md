---
hide:
    - toc
---
<img src="maraton.png" width=100>

# Półmaraton - predykcja czasu i statystyki

<div style="text-align: center; margin: 30px 0;">
    <a href="https://polmaraton.streamlit.app/" 
       target="_blank" 
       rel="noopener noreferrer"
       style="display: inline-block; 
              background-color: #ff4b4b; 
              color: white; 
              padding: 15px 30px; 
              text-decoration: none; 
              border-radius: 8px; 
              font-size: 18px; 
              font-weight: bold;
              box-shadow: 0 4px 8px rgba(0,0,0,0.2);
              transition: all 0.3s ease;">
        🔗 Półmaraton
    </a>
</div>

### Interaktywna aplikacja Streamlit, która analizuje swobodny opis biegacza za pomocą modelu GPT-4o-mini – automatycznie rozpoznaje imię, wiek, płeć i czas na 5 km. Waliduje oraz uzupełnia brakujące informacje przyjaznymi podpowiedziami AI. Przewiduje indywidualny czas półmaratonu na podstawie wytrenowanego modelu ML (na rzeczywistych danych Półmaratonu Wrocławskiego z lat 2023-2024, w sumie ponad 20tys. uczestników z obu lat). Prezentuje wynik w czytelnym formacie (hh:mm:ss) oraz statystyki: tempo na kilometr, średnią prędkość oraz kategorię poziomu biegacza. Generuje spersonalizowane, motywujące podsumowanie i wskazówki treningowe z wykorzystaniem OpenAI. Loguje dane anonimowo do Langfuse w celu monitoringu jakości modelu. Obsługuje wielopoziomowe źródła modelu (S3 → Supabase Storage → lokalnie) i jest w pełni konteneryzowana (Docker). Użytkownik otrzymuje natychmiastową, angażującą prognozę swojego wyniku oraz konkretne porady treningowe – wszystko w jednym, eleganckim interfejsie webowym. Aktualnie aplikacja działa w Streamlit Cloud i Supabase Storage, pierwotnie była funkcjonowała na Digital Ocean.

<div class="grid" markdown>
    Wykorzystane technologie i biblioteki
    * Python
    * Streamlit
    * Scikit-learn
    * PyCaret
    * CatBoost
    * Joblib
    * Pandas
    * NumPy
    * OpenAI GPT
    * Langfuse
    * AWS S3
    * Supabase Storage
    * DigitalOcean
    * Docker
    * Github
    * boto3
    * python-dotenv   
</div>