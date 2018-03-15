SUBDIRS = webrtc

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = webrtc-audio-processing.pc

webrtcincludedir = $(includedir)/webrtc_audio_processing
nobase_webrtcinclude_HEADERS = webrtc/api/video/video_rotation.h \
			       webrtc/api/video/video_content_type.h \
			       webrtc/api/video/video_timing.h \
			       webrtc/api/audio/audio_frame.h \
			       webrtc/api/rtp_headers.h \
			       webrtc/rtc_base/arraysize.h \
			       webrtc/rtc_base/deprecation.h \
			       webrtc/rtc_base/array_view.h \
			       webrtc/rtc_base/checks.h \
			       webrtc/rtc_base/refcount.h \
			       webrtc/rtc_base/scoped_ref_ptr.h \
			       webrtc/rtc_base/constructormagic.h \
			       webrtc/rtc_base/basictypes.h \
			       webrtc/api/optional.h \
			       webrtc/api/array_view.h \
			       webrtc/api/audio/echo_canceller3_config.h \
			       webrtc/api/audio/echo_control.h \
			       webrtc/rtc_base/platform_file.h \
			       webrtc/rtc_base/numerics/safe_compare.h \
			       webrtc/rtc_base/numerics/safe_conversions.h \
			       webrtc/rtc_base/numerics/safe_conversions_impl.h \
			       webrtc/rtc_base/sanitizer.h \
			       webrtc/rtc_base/type_traits.h \
			       webrtc/rtc_base/timeutils.h \
			       webrtc/common_types.h \
			       webrtc/typedefs.h \
			       webrtc/modules/audio_processing/beamformer/array_util.h \
			       webrtc/modules/audio_processing/include/audio_generator.h \
			       webrtc/modules/audio_processing/include/audio_frame_view.h \
			       webrtc/modules/audio_processing/include/audio_processing.h \
			       webrtc/modules/audio_processing/include/audio_processing_statistics.h \
			       webrtc/modules/audio_processing/include/config.h \
			       webrtc/modules/include/module_common_types.h \
			       webrtc/modules/include/module_fec_types.h \
			       webrtc/modules/include/module_common_types_public.h \
			       webrtc/modules/video_coding/codecs/h264/include/h264_globals.h \
			       webrtc/modules/video_coding/codecs/vp8/include/vp8_globals.h \
			       webrtc/modules/video_coding/codecs/vp9/include/vp9_globals.h \
			       webrtc/modules/video_coding/codecs/interface/common_constants.h

EXTRA_DIST = NEWS \
	     README.md \
	     UPDATING.md
