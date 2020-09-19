Fedor Odintsov

Contacts:
E-mail: fadmin@list.ru
Telegram: @Fodinsoft

Objectives:
I want to become a web-developer. I have analytical mind-set, understaning of progamming and I feel the beauty of a code.

Skills:
I experienced in: Basic, Assembler (Z-80, PDP-11), C, C++, Pascal, VBA, Python, Lua, JS, Bash, SQL, HTML, CSS. Frameworks: jQuery, Bootstrap.

Code examples:
	export class ComplexNumber {
		constructor(real, imag = 0){
			[this.real, this.imag] = [real, imag];
		}

		add(n){
			return new ComplexNumber(this.real + n.real, this.imag + n.imag);
		}

		sub(n){
			return this.add(new ComplexNumber(-n.real, -n.imag));
		}

		mul(n){
			const [a, b] = [this.real, this.imag], [c, d] = [n.real, n.imag];
			return new ComplexNumber(a * c - b * d, a * d + b * c);
		}

		div(n){
			const [a, b] = [this.real, this.imag], [c, d] = [n.real, n.imag];
			return new ComplexNumber(
				(a * c + b * d)/(c * c + d * d),
				(b * c - a * d)/(c * c + d * d));
		}

		get abs(){
			return Math.sqrt(this.real ** 2 + this.imag ** 2);
		}

		get conj(){
			return new ComplexNumber(this.real, 0 - this.imag);
		}

		get exp(){
			const [a, b] = [this.real, this.imag];
			return new ComplexNumber(Math.exp(a) * Math.cos(b), Math.exp(a) * Math.sin(b));
		}
	}

Work experience:
System administrator, polygraphic designer. I've never worked as a programmer except for freelance

Education:
Yuzhno-Sakhalinsk State Institute, Bachelor of Mathematics and Informatics.
I studied at Coursera.org, Stepik.org (I have obtained gold certificates in the following courses: "Python programming", "C/C++ multithread programming", "Linux Basic progamming", "C++ progamming").

English:
I can read technical docs without dictionary. I can write, speak and understand listening a little bit worse. My level is between A2 and B1.