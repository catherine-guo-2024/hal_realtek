zephyr_library()

zephyr_library_sources_ifdef(CONFIG_REALTEK_TIM rtl_tim.c)
zephyr_library_sources_ifdef(CONFIG_REALTEK_ENHTIM rtl_enh_tim.c)
