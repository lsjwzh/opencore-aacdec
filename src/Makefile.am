lib_LTLIBRARIES = libaacdec.la

libaacdec_la_LDFLAGS = -version-info 1:0:0 $(libtool_flags)

libaacdec_la_CFLAGS = -I$(top_srcdir)/oscl -I$(top_srcdir)/include

libaacdecdir = $(includedir)/libaacdec

libaacdec_la_SOURCES = analysis_sub_band.c \
	apply_ms_synt.c \
	apply_tns.c \
	buf_getbits.c \
	byte_align.c \
	calc_auto_corr.c \
	calc_gsfb_table.c \
	calc_sbr_anafilterbank.c \
	calc_sbr_envelope.c \
	calc_sbr_synfilterbank.c \
	check_crc.c \
	dct16.c \
	dct64.c \
	decode_huff_cw_binary.c \
	decode_noise_floorlevels.c \
	deinterleave.c \
	digit_reversal_tables.c \
	dst16.c \
	dst32.c \
	dst8.c \
	esc_iquant_scaling.c \
	extractframeinfo.c \
	fft_rx4_long.c \
	fft_rx4_short.c \
	fft_rx4_tables_fxp.c \
	find_adts_syncword.c \
	fwd_long_complex_rot.c \
	fwd_short_complex_rot.c \
	gen_rand_vector.c \
	get_adif_header.c \
	get_adts_header.c \
	get_audio_specific_config.c \
	get_dse.c \
	get_ele_list.c \
	getfill.c \
	get_ga_specific_config.c \
	getgroup.c \
	getics.c \
	get_ics_info.c \
	getmask.c \
	get_prog_config.c \
	get_pulse_data.c \
	get_sbr_bitstream.c \
	get_sbr_startfreq.c \
	get_sbr_stopfreq.c \
	get_tns.c \
	getactualaacconfig.c \
	hcbtables_binary.c \
	huffcb.c \
	huffdecode.c \
	hufffac.c \
	huffspec_fxp.c \
	idct16.c \
	idct32.c \
	idct8.c \
	imdct_fxp.c \
	infoinit.c \
	init_sbr_dec.c \
	intensity_right.c \
	inv_long_complex_rot.c \
	inv_short_complex_rot.c \
	iquant_table.c \
	long_term_prediction.c \
	long_term_synthesis.c \
	lt_decode.c \
	mdct_fxp.c \
	mdct_tables_fxp.c \
	mdst.c \
	mix_radix_fft.c \
	ms_synt.c \
	pns_corr.c \
	pns_intensity_right.c \
	pns_left.c \
	ps_allocate_decoder.c \
	ps_all_pass_filter_coeff.c \
	ps_all_pass_fract_delay_filter.c \
	ps_applied.c \
	ps_bstr_decoding.c \
	ps_channel_filtering.c \
	ps_decode_bs_utils.c \
	ps_decorrelate.c \
	ps_fft_rx8.c \
	ps_hybrid_analysis.c \
	ps_hybrid_filter_bank_allocation.c \
	ps_hybrid_synthesis.c \
	ps_init_stereo_mixing.c \
	ps_pwr_transient_detection.c \
	ps_read_data.c \
	ps_stereo_processing.c \
	pulse_nc.c \
	pv_div.c \
	pv_log2.c \
	pvmp4audiodecoderconfig.c \
	pvmp4audiodecoderframe.c \
	pvmp4audiodecodergetmemrequirements.c \
	pvmp4audiodecoderinitlibrary.c \
	pvmp4audiodecoderresetbuffer.c \
	pvmp4setaudioconfig.c \
	pv_normalize.c \
	pv_pow2.c \
	pv_sine.c \
	pv_sqrt.c \
	qmf_filterbank_coeff.c \
	q_normalize.c \
	sbr_aliasing_reduction.c \
	sbr_applied.c \
	sbr_code_book_envlevel.c \
	sbr_crc_check.c \
	sbr_create_limiter_bands.c \
	sbr_dec.c \
	sbr_decode_envelope.c \
	sbr_decode_huff_cw.c \
	sbr_downsample_lo_res.c \
	sbr_envelope_calc_tbl.c \
	sbr_envelope_unmapping.c \
	sbr_extract_extended_data.c \
	sbr_find_start_andstop_band.c \
	sbr_generate_high_freq.c \
	sbr_get_additional_data.c \
	sbr_get_cpe.c \
	sbr_get_dir_control_data.c \
	sbr_get_envelope.c \
	sbr_get_header_data.c \
	sbr_get_noise_floor_data.c \
	sbr_get_sce.c \
	sbr_inv_filt_levelemphasis.c \
	sbr_open.c \
	sbr_read_data.c \
	sbr_requantize_envelope_data.c \
	sbr_reset_dec.c \
	sbr_update_freq_scale.c \
	set_mc_info.c \
	sfb.c \
	shellsort.c \
	synthesis_sub_band.c \
	tns_ar_filter.c \
	tns_decode_coef.c \
	tns_inv_filter.c \
	trans4m_freq_2_time_fxp.c \
	trans4m_time_2_freq_fxp.c \
	unpack_idx.c \
	window_tables_fxp.c

noinst_HEADERS = \
	aac_mem_funcs.h \
	analysis_sub_band.h \
	apply_ms_synt.h \
	apply_tns.h \
	bit_reversal_swap.h \
	buf_getbits.h \
	calc_auto_corr.h \
	calc_sbr_anafilterbank.h \
	calc_sbr_envelope.h \
	calc_sbr_synfilterbank.h \
	chans.h \
	check_crc.h \
	dct16.h \
	dct64.h \
	decode_noise_floorlevels.h \
	digit_reversal_tables.h \
	dst16.h \
	dst32.h \
	dst8.h \
	e_adif_const.h \
	e_blockswitching.h \
	e_coupling_mode.h \
	e_elementid.h \
	e_huffmanconst.h \
	e_infoinitconst.h \
	e_invf_mode.h \
	e_maskstatus.h \
	e_mp4ff_const.h \
	e_progconfigconst.h \
	e_rawbitstreamconst.h \
	e_sbr_element_id.h \
	e_sbr_error.h \
	e_sbr_header_status.h \
	e_sbr_master_status.h \
	e_sbr_sync_state.h \
	esc_iquant_scaling.h \
	e_sr_mode.h \
	e_tns_const.h \
	e_window_sequence.h \
	e_window_shape.h \
	extractframeinfo.h \
	fft_rx4.h \
	find_adts_syncword.h \
	fwd_long_complex_rot.h \
	fwd_short_complex_rot.h \
	fxp_mul32_arm_gcc.h \
	fxp_mul32_arm_v4_gcc.h \
	fxp_mul32_arm_v4.h \
	fxp_mul32_arm_v5.h \
	fxp_mul32_c_equivalent.h \
	fxp_mul32_c_msc_evc_armv5.h \
	fxp_mul32_c_msc_evc.h \
	fxp_mul32.h \
	fxp_mul32_pentium.h \
	gen_rand_vector.h \
	get_adif_header.h \
	get_adts_header.h \
	get_audio_specific_config.h \
	getbits.h \
	get_dse.h \
	get_ele_list.h \
	getfill.h \
	get_ga_specific_config.h \
	get_ics_info.h \
	get_prog_config.h \
	get_pulse_data.h \
	get_sbr_bitstream.h \
	get_sbr_startfreq.h \
	get_sbr_stopfreq.h \
	get_sign_bits.h \
	get_tns.h \
	hcbtables.h \
	huffman.h \
	ibstream.h \
	idct16.h \
	idct32.h \
	idct8.h \
	imdct_fxp.h \
	init_sbr_dec.h \
	intensity_right.h \
	inv_long_complex_rot.h \
	inv_short_complex_rot.h \
	iquant_table.h \
	long_term_prediction.h \
	long_term_synthesis.h \
	lt_decode.h \
	ltp_common_internal.h \
	lt_prediction.h \
	mdct_fxp.h \
	mdst.h \
	mix_radix_fft.h \
	ms_map_mask.h \
	ms_synt.h \
	pns_corr.h \
	pns_intensity_right.h \
	pns_left.h \
	ps_allocate_decoder.h \
	ps_all_pass_filter_coeff.h \
	ps_all_pass_fract_delay_filter.h \
	ps_applied.h \
	ps_bstr_decoding.h \
	ps_channel_filtering.h \
	ps_constants.h \
	ps_decode_bs_utils.h \
	ps_decorrelate.h \
	ps_fft_rx8.h \
	ps_hybrid_analysis.h \
	ps_hybrid_filter_bank_allocation.h \
	ps_hybrid_synthesis.h \
	ps_init_stereo_mixing.h \
	ps_pwr_transient_detection.h \
	ps_read_data.h \
	ps_stereo_processing.h \
	pulse_nc.h \
	pv_div.h \
	pv_log2.h \
	pv_normalize.h \
	pv_pow2.h \
	pv_sine.h \
	pv_sqrt.h \
	qmf_filterbank_coeff.h \
	q_normalize.h \
	s_adif_header.h \
	s_bit_buffer.h \
	s_bits.h \
	sbr_aliasing_reduction.h \
	sbr_applied.h \
	sbr_code_book_envlevel.h \
	sbr_constants.h \
	sbr_crc_check.h \
	sbr_create_limiter_bands.h \
	sbr_dec.h \
	sbr_decode_envelope.h \
	sbr_decode_huff_cw.h \
	sbr_downsample_lo_res.h \
	sbr_envelope_calc_tbl.h \
	sbr_envelope_unmapping.h \
	sbr_extract_extended_data.h \
	sbr_find_start_andstop_band.h \
	sbr_generate_high_freq.h \
	sbr_get_additional_data.h \
	sbr_get_cpe.h \
	sbr_get_dir_control_data.h \
	sbr_get_envelope.h \
	sbr_get_header_data.h \
	sbr_get_noise_floor_data.h \
	sbr_get_sce.h \
	sbr_inv_filt_levelemphasis.h \
	sbr_open.h \
	sbr_read_data.h \
	sbr_requantize_envelope_data.h \
	sbr_reset_dec.h \
	sbr_update_freq_scale.h \
	s_ch_info.h \
	s_crc_buffer.h \
	s_elelist.h \
	set_mc_info.h \
	sfb.h \
	s_frameinfo.h \
	s_hcb.h \
	shellsort.h \
	s_huffman.h \
	s_hybrid.h \
	s_lt_pred_status.h \
	s_mc_info.h \
	s_mixdown.h \
	s_patch.h \
	s_progconfig.h \
	s_ps_dec.h \
	s_pulseinfo.h \
	s_sbrbitstream.h \
	s_sbr_channel.h \
	s_sbr_dec.h \
	s_sbr_element_stream.h \
	s_sbr_frame_data.h \
	s_sbr_header_data.h \
	s_sectinfo.h \
	s_sr_info.h \
	s_tdec_int_chan.h \
	s_tdec_int_file.h \
	s_tnsfilt.h \
	s_tns_frame_info.h \
	s_wnd_shape.h \
	synthesis_sub_band.h \
	tns_ar_filter.h \
	tns_decode_coef.h \
	tns_inv_filter.h \
	unpack_idx.h \
	window_block_fxp.h
