# Makefile for the Linux transform drivers on sunxi platform.
# 10 jun 2014, Tyle, <mailto:tyle@allwinnertech.com>
# Rewritten to use lists instead of if-statements.

obj-$(CONFIG_SUNXI_TRANSFORM) += sunxi_tr.o

sunxi_tr-y := sunxi_transform.o
sunxi_tr-$(CONFIG_ARCH_SUN8IW6) += sun8iw6_transform.o
