���L�̊J���������K�C�h
�EOS Ubuntu precise 64
�EPHP 5.5.3
�EMySQL 5.5
�Enginx 1.1.19


���\�z�菇
1)Vagrant�T�C�g���A�ŐV�ł�Vagrant���_�E�����[�h���A�C���X�g�[��������
http://downloads.vagrantup.com/
2)���l��Virtualbox���C���X�g�[������
https://www.virtualbox.org/wiki/Downloads
3)�{"Miso Development Environment"�̃\�[�X�ꎮ��git�Ŏ�����PC�Ƀ_�E�����[�h����
4)���L�́u�t�H���_�\���v�ɏ]���A���t�H���_���\������
5)�R�}���h���C������Vagrantfile�̂���t�H���_�Ɉړ����A���L�̃R�}���h�����s����
Vagrant up
6)�u���E�U���A���L�̃����N�Ő���Ɋ����ł������ǂ������`�F�b�N����
http://127.0.0.1:8080/
���菇5)�����s����O�ɑ��̃T�[�r�X���|�[�g8080���g���Ă��邩�`�F�b�N����K�v������

�����e
OS Ubuntu precise 64
PHP 5.5.3
MySQL 5.5
nginx 1.1.19
Document Root
/vagrant_data/www
�t�H���_�\��
.
������ Environment
�� ������ Vagrantfile
�� ������ cookbooks
�� ������ omusubi
�� ������ README.md
�� ������ attributes
�� �� ������ default.rb
�� ������ recipes
�� �� ������ default.rb
�� �� ������ gentoo.rb
�� ������ templates
�� ������ default
�� ������ php-fpm.conf.erb
�� ������ www2.conf.erb
������ Source
������ www
������ index.php

Source�t�H���_�̓Q�X�gOS��/vagrant_data�t�H���_�ƘA��
Source�t�H���_��Git�ł͊Ǘ����Ă��Ȃ��̂Ŏ����ō쐬

�A�N�Z�X�����N
http://127.0.0.1:8080/