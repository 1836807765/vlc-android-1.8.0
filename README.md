��Ϊ����tar.gzѹ����ʽ, �ļ��Ƚϴ�,��ʱ�ŵ��ٶ�����,�Ժ���µ����� ���ص�ַ��: http://pan.baidu.com/s/1dEjE6rR

this is vlc-android version all source code .compiled by LanSoSdk team.
compile step by :https://wiki.videolan.org/AndroidCompile#Requirements
in codes, we add some MediaPlayer motheds, so you can calling libvlc like this:
	
							mMediaPlayer = new MediaPlayer(this);
        	  	mMediaPlayer.setVideoView(mSurfaceView); 
        	  	mMediaPlayer.setOnVideoSizeChangedListener(this);
        	  	mMediaPlayer.setDataSource(mUri,isSwCodec);
             	mMediaPlayer.setEventListener(mMediaPlayerListener);
             	mMediaPlayer.setOnHardwareAccelerationErrorListener(this);
              mMediaPlayer.play();

	belove demo in VideoPlayerActivity2.java. 	
	Hope Enjoy.
-------------------------->
Ϊ�˴�Ҹ��õĵ���,���Ƕ�MediaPlayer��������һЩ����, ������ҿ���ֱ�Ӳο�VideoPlayerActivity2.java�е�д��, ��ʹ��vlc-android.

������ȫ����:
		https://wiki.videolan.org/AndroidCompile#Requirements �Ĳ����������.
	(������ǳ�ѧ��,�����½�һ�������,��ȫ����)

�˴�����LanSoSdk�����,��ȫû��clean�Ĵ���,��������еĸ��������ļ�,.o�ļ����Ǵ��ڵ�.
�������ܿ�ı���,�����ú�������ȫһ�µ�·��,����ubuntu���û���.�ļ�·����/home/sno/vlc_android17/xxxԴ����.

	
���ǵı������
   ϵͳwin7�а�װ�����,����װubuntu12.04(64λ)(ͬ����ubuntu14.04һ�����Ա���ɹ�).
  ���ֻ�������(my env is):
   	export JAVA_HOME=/home/sno/android_tools/jdk1.7.0_51
		export JRE_HOME=/home/sno/android_tools/jdk1.7.0_51/jre
		export ANDROID_ABI=armeabi-v7a
		export ANDROID_SDK=/home/sno/android_tools/adt-bundle-linux-x86_64-20140321/sdk
		export PATH=$PATH:$ANDROID_SDK/platform-tools:$ANDROID_SDK/tools
		export ANDROID_NDK=/home/sno/android_tools/ndk/android-ndk-r10e

 
������github��issue�����۸�������������,��������Ӣ��,�Ա����ĸ��ֵĴ�ţ����, һ������.

(�Ŷӽ���)	
 �������ɿƼ����޹�˾.LanSoSdk�Ŷ�, רҵ����ý������Ƶ�ķ�����˾.������Ƶ�ɼ�,�༭,����, ����,����,����,���ŵ�.
   
 ����ʹ��vlc���������Ŀ, �������������vlc-android���ĸ߼�����,��ӭ�������.��ʾ��ַ:https://github.com/LanSoSdk/LanSoSdkPlayDemo
 1,������Ƶ���ػ�������С,������Ƶ����ʱ��.	
 2,��Ƶ����,��֡����.	
 3,��Ƶ�����ٶȿɵ�,�����ٶȿɵ�.
 4,��Ӳ���Զ��л�.��ȫ֧����Ӳ��.����⹦��֧��NEONָ��,���߳̽���.
 5,��Ƶ¼��.	
 6,������Ƶ֧�ֱ߲��š������ع���. ֧�ֿ���ȫ������.----���粻̫��,��ʹ��3G/4G�����Ҳ������������.	
 7,������Ƶ,�鿴��ǰ����ٷֱ�, �鿴��ǰ����.----	
 8,֧�ֶԱȶ�, ���Ͷ�,ɫ��,��ɫ��ȡ,����,��̬���,������12�ֹ���,���ɶ����˾�Ч��.  ----��������,����,���ֵĹ���.	
 9,֧������3D, ����3D����.	
 10,RTSP����Ƶֱ��ʱ���ӳ�����(����).	
 11,RTSP����ʱ���������ص�����(����).	
 12,Ӳ���ڲ����ֻ��ϲ�֧�ֵ�����(����).	
 13,M3U8���粥��ʱcrash������(����).	
 14,playlistʱ�����϶�������(����).	
 15,�������Ŀ�������ĸ�����Ƶ���������(����).		
 
 
 
 Emai: support@lansongtech.com, QQȺ 235842416; ������ϵ1852600324(busy)