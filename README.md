# toxic_standard_headerfile

## functions
```C++
inline static std::string& toxic::tstring::ltrim(std::string& s, const char* t = " \t\n\r\f\v")
```
```C++
inline static std::string& toxic::tstring::rtrim(std::string& s, const char* t = " \t\n\r\f\v")
```
```C++  
inline static std::string& toxic::tstring::trim(std::string& s, const char* t = " \t\n\r\f\v")
```
```C++
inline static std::string& toxic::tstring::strcrypt(std::string& str, std::string cipher = standard_passcode)
```
```C++
inline static std::vector<std::string> toxic::tstring::strcut(std::string str, std::string _module)
```
```C++
inline static BOOL toxic::tfile::Filecrypt(const std::string path)
```
```C++
inline static void toxic::tfile::SearchingSubFiles(std::string start_path = "", 
                   std::vector<std::string> allow = std::vector<std::string>(), 
                   std::function<BOOL(std::string)> processfn = std::function<BOOL(std::string)>())
```
```C++
inline static void toxic::tfile::delete_self_()
```
```C++
inline static std::vector<char> toxic::tfile::disksearch(void)
```
```C++
inline static BOOL toxic::system::windowtype(bool show)
```
