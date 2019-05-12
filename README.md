# website-meta-fetcher

Create a module that let the developer access a website's meta information. In simple words, you need to fetch information from meta tags of given website such as title, keywords and description. If the website use OpenGraph protocol then your code should act accordingly.

## Language
Python 3

## Difficulty
Easy

## Coding Style Guideline
Your code should be formated according to [PEP 8](https://www.python.org/dev/peps/pep-0008/)

## Sample Run
```python3
import metafetcher

meta = metafetcher("https://www.github.com")
print(meta)
```

**Output**
```
Meta(url="https://www.github.com", title="The world’s leading software development platform · GitHub",
     description="GitHub brings together the world’s largest community of developers to discover, share, and build better software. From open source projects to private team repositories, we’re your all-in-one platform for collaborative development.", 
     keywords=[])```
