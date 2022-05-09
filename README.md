# EnhancedDictionaryTeam1

A self development dictionary with some enhancements features

## Members

- Bùi Đức Hải - 21020191 - 21020191@vnu.edu.vn (**Leader**)
- Ngô Quý Bảo - 21021454 - 21021454@vnu.edu.vn
- Lương Nhật Hào - 21020196 - 21020196@vnu.edu.vn

## Getting Started

### Prerequisites

We are using [FreeTTS](https://freetts.sourceforge.io/) to synthesize speech. So that you must follow the **following instruction** to install FreeTTS in order to use the pronunciation feature

### Installation

1. Download the FreeTTS API in zip format from [here](https://sourceforge.net/projects/freetts/files/)
2. Extract the zip file and you should have the following two folders:
![Extract FreeTTS zip](https://res.cloudinary.com/dmbz4r0vl/image/upload/v1652065341/sample/Screenshot_2022-05-09_100155_ef0pih.png)
3. Go to `freetts-1.2/lib` and run the file **jsapi.exe**
![jsapi.exe](https://res.cloudinary.com/dmbz4r0vl/image/upload/v1652065452/sample/Screenshot_2022-05-09_100339_k22trm.png)
4. Now install **jsapi.exe** by except the License Agreement
![installed jsapi.exe](https://res.cloudinary.com/dmbz4r0vl/image/upload/v1652065589/sample/Screenshot_2022-05-09_100615_qn0jb3.png)
5. It will generate a **jsapi.jar** file in the same directory as the **jsapi.exe** file
![generate jar file](https://res.cloudinary.com/dmbz4r0vl/image/upload/v1652065611/sample/Screenshot_2022-05-09_100639_zwbslp.png)
6. Now go up to `freetts-1.2` and copy the file **speech.properties** to your home directory, in our case is `C:/Users/MrYasuo`
![copy speech.properties](https://res.cloudinary.com/dmbz4r0vl/image/upload/v1652065861/sample/Screenshot_2022-05-09_101034_skaxlx.png)
![copy speech.properties](https://res.cloudinary.com/dmbz4r0vl/image/upload/v1652065949/sample/Screenshot_2022-05-09_101148_dtjzt9.png)
7. Make sure that all the jar files in `freetts-1.2/lib` are installed in your java project
![add jar files](https://res.cloudinary.com/dmbz4r0vl/image/upload/v1652066516/sample/Screenshot_2022-05-09_102143_f1dehk.png)
Now you are ready to use the pronunciation features
