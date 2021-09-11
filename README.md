# JupyterLab-Docker

## Overview
- ubuntuベースである
- encodingはja_JP.UTF-8に設定，timizoneはAsia/Tokyoに設定
- Pystan，Rstan環境を構築

## 動作環境（確認済）
- macOS BigSur
- Docker Desktop(macOS)

## Install
"""
git clone git@github.com:yuiki-iwayama/JupyterLab-Docker.git
cd JupyterLab-Docker
docker-compose up -d --build
"""

## Usage
http://localhost:8888

## Document
- workディレクトリを配置