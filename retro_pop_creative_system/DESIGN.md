---
name: Retro-Pop Creative System
colors:
  surface: '#FFFFFF'
  surface-dim: '#eed3de'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0f5'
  surface-container: '#ffe8f1'
  surface-container-high: '#fce1ed'
  surface-container-highest: '#f6dbe7'
  on-surface: '#26171f'
  on-surface-variant: '#58404c'
  inverse-surface: '#3c2c34'
  inverse-on-surface: '#ffecf3'
  outline: '#8b6f7d'
  outline-variant: '#dfbdcd'
  surface-tint: '#b30086'
  primary: '#ae0083'
  on-primary: '#ffffff'
  primary-container: '#da00a4'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffaeda'
  secondary: '#666000'
  on-secondary: '#ffffff'
  secondary-container: '#f0e400'
  on-secondary-container: '#6a6500'
  tertiary: '#7b5500'
  on-tertiary: '#ffffff'
  tertiary-container: '#9b6b00'
  on-tertiary-container: '#fffbff'
  error: '#E53935'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd8ea'
  primary-fixed-dim: '#ffaeda'
  on-primary-fixed: '#3c002b'
  on-primary-fixed-variant: '#890066'
  secondary-fixed: '#f3e700'
  secondary-fixed-dim: '#d5ca00'
  on-secondary-fixed: '#1e1c00'
  on-secondary-fixed-variant: '#4d4800'
  tertiary-fixed: '#ffdeac'
  tertiary-fixed-dim: '#ffba38'
  on-tertiary-fixed: '#281900'
  on-tertiary-fixed-variant: '#604100'
  background: '#F7F4EF'
  on-background: '#26171f'
  surface-variant: '#f6dbe7'
  border-accent: '#D8BFF3'
  success: '#20B26B'
  text-main: '#1A1A1A'
  text-muted: '#666666'
typography:
  headline-xl:
    fontFamily: Syne
    fontSize: 96px
    fontWeight: '800'
    lineHeight: '1.0'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-xl-mobile:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '600'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  4xl: 96px
  5xl: 120px
---

name: "Frisca — Y2K Retro Creative Portfolio"
description: "Responsive personal portfolio for a DKV student, illustrator, and visual creator combining Y2K retro pop, sticker collage, and scrapbook aesthetics."
colors:
  primary: "#FF2BC2"
  secondary: "#FFF200"
  tertiary: "#FFB300"
  background: "#F7F4EF"
  surface: "#FFFFFF"
  text-primary: "#1A1A1A"
  text-secondary: "#666666"
  border: "#D8BFF3"
  success: "#20B26B"
  warning: "#FFB300"
  error: "#E53935"
typography:
  h1:
    fontFamily: "Bold geometric display sans-serif"
    fontSize: 6rem
    fontWeight: 900
    lineHeight: 1.0
    letterSpacing: "-0.02em"
  h2:
    fontFamily: "Bold geometric display sans-serif"
    fontSize: 4rem
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  h3:
    fontFamily: "Bold geometric display sans-serif"
    fontSize: 2rem
    fontWeight: 700
    lineHeight: 1.2
  body-md:
    fontFamily: "Readable sans-serif"
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.6
  label-sm:
    fontFamily: "Readable sans-serif"
    fontSize: 0.75rem
    fontWeight: 600
rounded:
  sm: "8px"
  md: "12px"
  lg: "20px"
  xl: "24px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "64px"
  4xl: "96px"
  5xl: "120px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.background}"
    rounded: "{rounded.full}"
    padding: "12px 24px"
  button-primary-hover:
    backgroundColor: "{colors.secondary}"
  button-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.full}"
    padding: "12px 24px"
  card:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.md}"
    padding: "12px 14px"
