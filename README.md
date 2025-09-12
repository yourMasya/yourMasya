# About me

```
class Expertise(Me):
  name: str = 'Maxim Matvejev'
  bachelor: str = 'HSE Fundamental and Computational Linguistics'
  minor: str = 'Intellectual Data Analysis',
  thesis: str = 'Comparison of Rule-based and Deep Learning Disambiguation Models on Bi-aspectual Verb Data'

  languages: Dict[str, str] = {
    'Russian': 'Native',
    'English': 'C1',
    'German': 'A2'
  }

  code: List[str] = ['python', 'sql']
  
  technologies: Dict[str, List[str]] {
      'nlp': ['spacy','pymorphy3', 'pymystem3', 'nltk', 're', 'natasha', 'gensim', 'stanza'],
      'llm': ['langchain', 'langsmith', 'openaiapi'],
      'ml': ['scikit-learn', 'catboost', 'xgboost', 'lightgbm', 'numpy'],
      'dl': ['pytorch', 'tensorflow', 'transformers'],
      'analytics': ['pandas'],
      'visualization': ['seaborn', 'matplotlib', 'plotly'],
      'scraping': ['bs4', 'selenium'],
      'databases': ['postgresql', 'chromadb', 'mongodb', 'elasticsearch'],
      'os': ['windows'],
      'other': ['fastapi', 'w&b', 'torchaudio', 'torchvision']
    }
  
  cv: str = 'https://docs.google.com/document/d/1SNaiJOuf3XrUo_zUvtTL52_Mir364S6L7jR4UsZt3tI/edit?usp=sharing'
  
  contacts: Dict[str, str] = {
      'telegram': '@your_masya',
      'email': 'mmatvs@mail.ru'
    }
