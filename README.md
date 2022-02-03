# toxic_standard_headerfile

## functions
syntax:\n
```C++
inline static std::string& toxic::tstring::ltrim(std::string& s, const char* t = " \t\n\r\f\v")
```
args - s : trim target string\n
       t : delete target character\n
purpose : left trim about argument(std::string& s)\n
return std::string\n
___
syntax:
```C++
inline static std::string& toxic::tstring::rtrim(std::string& s, const char* t = " \t\n\r\f\v")
```
args - s : trim target string
       t : delete target character
purpose : right trim about argument(std::string& s)
return std::string
___
```C++
inline static std::string& toxic::tstring::trim(std::string& s, const char* t = " \t\n\r\f\v")
```
args - s : trim target string
       t : delete target character
purpose : trim about argument(std::string& s)
return std::string
___
```C++
inline static std::string& toxic::tstring::strcrypt(std::string& str, std::string cipher = standard_passcode)
```
___
```C++
inline static std::vector<std::string> toxic::tstring::strcut(std::string str, std::string _module)
```
___
```C++
inline static BOOL toxic::tfile::Filecrypt(const std::string path)
```
___
```C++
inline static void toxic::tfile::SearchingSubFiles(std::string start_path = "", 
                   std::vector<std::string> allow = std::vector<std::string>(), 
                   std::function<BOOL(std::string)> processfn = std::function<BOOL(std::string)>())
```
___
```C++
inline static void toxic::tfile::delete_self_()
```
___
```C++
inline static std::vector<char> toxic::tfile::disksearch(void)
```
___
```C++
inline static BOOL toxic::system::windowtype(bool show)
```
