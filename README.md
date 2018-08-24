pythontool
==========
c言語からpythonのライブラリを使用したツール集です。

## Description ##
### ツールの種類 ###
* pyimpinfo  
  pythonのimp情報表示
  - 定数
  - suffixs、suffix、mode、type
* pyosinfo  
  pythonのos情報表示
  - uname
  - id情報
  uid、gid、groups、egid、euid  
  - devnull、login、ppid、pid、pardir、sep、defpath、cwd、name
* pysiteinfo  
  pythonのsite情報表示
  - check_enableusersite、ENABLE_USER_SITE、USER_SITE、USER_BASE、PREFIXES、site module
* pysysconfiginfo  
  pythonのsysconfig情報表示
  - PREFIX、EXEC_PREFIX、python_version、python_inc、python_lib
* pysysinfo  
  pythonのsys情報表示  
  - platform、path、version、copyright
  - prefix  
    prefix、exec_prefix  
  - Encoding
  fileSystemEncoding、defaultEncoding
* pytarinfo  
  pythonのtarfile情報  
  - ファイルサイズ、ファイル名
* pypilinfo  
  - dspimage  
  画像ファイル表示プログラム
  - pypilinfo
  画像の情報を表示
    - 画像フォーマット
    - サイズ
    - カラーモード
* pyrpminfo  
  - pyrpminfo  
  rpmファイル情報を表示
    - rpmのversion
    - Name-Version-Release
    - Distribution
    - Vendor
    - License
    - Packager
  - pyrpmtaginfo  
  rpmのtagnames情報表示
* pyclz  
  - pyclz2
  - pyclz3
* pypass  
  pythonのgetpass情報を表示
    - getuser

## Demo ##

## VS. ##

## Requirement ##
VineLinux ver 6.5に付属しているpythonに依存

## Usage ##
* pyimpinfo  
  $ pyimpinfo  
* pyosinfo  
  $ pyosinfo
* pysiteinfo  
  $ pysiteinfo
* pysysconfiginfo  
  $ pysysconfiginfo
* pysysinfo  
  $ pysysinfo
* pytarinfo  
  $ pytarinfo tarfile
* pypilinfo  
  $ pyimage 画像ファイル名
* pyrpminfo  
  $ pyrpminfo rpmファイル
* pyrpmtaginfo  
  $ pyrpmtaginfo
* pylz  
  $ pylz2  
  $ pylz3  
* pypass  
  $ pyuser

## install ##
    git clone https://github.com/siranovel/pythontool.git  
    cd pythontool  
    rpm -ivh <rpmファイル名>  

## Contribution ##

## Licence ##

## Author ##
