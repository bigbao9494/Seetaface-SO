����,��Android SDK ���������غ�NDK

�������ص�: D:\Android\sdk\ndk-bundle

�������д���, ���뵽Ŀ¼ SeetafaceSO\app\src\main

��Ŀ¼��ִ�� D:\Android\sdk\ndk-bundle\ndk-build ���ɱ���

��ͬ�汾�ı����������ͬ 

* �����κΰ汾����Ҫ -fstrict-aliasing

* ���� arm64-v8a �� x86 �汾ֻ����-fstrict-aliasing ������ɾ��

* ���� armeabi �汾����� -mfloat-abi=softfp -mfpu=neon

* ���� armeabi-v7a �汾����� -fprefetch-loop-arrays -mfpu=neon

ע���� SeetafaceSO\app\src\main\jni\Application.mk �ļ��еĲ��� NDK_TOOLCHAIN_VERSION=4.9

�汾��Ҫ��NDKĿ¼�µ�toolchains�ļ����ڵ��ļ��������ְ汾һ��,�������е�·����:
D:\Android\sdk\ndk-bundle\toolchains


libsĿ¼�ṩ���ұ���õĸ���ƽ̨�İ汾,ע���������õİ汾û�������������

 public native FaceData[] TakeFacesFeatures(Bitmap vBmp);
 
����������Һ������ȥ��,����û��Ϊ��������汾, ��ʵ����DetectFaces���������һЩ���ò������޵���