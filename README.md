# ford

void main()
{
	float a, b, c, d;
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\n");
			printf("x1=%4.2f", 0.5 *(-b - sqrt(d)) / a);
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
}

	if ((ngan == 0) && van)
		cout << " khong ngan ";
	else if (ngan)
		cout << doc[ngan - 1] << " ngan ";

	if ((tram == 0) && (van || ngan))
		cout << " khong tram ";
	else if (tram)
		cout << doc[tram - 1] << " tram ";

	if ((chuc == 0) && donvi && (van || ngan || tram))
		cout << "le ";
	else if (chuc == 1)
		cout << " muoi ";
	else
		cout << doc[chuc - 1] << " muoi ";
	if (donvi)
		cout << doc[donvi - 1];
	getch();
void main()
{
	float a, b, c, d;
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\n");
			printf("x1=%4.2f", 0.5 *(-b - sqrt(d)) / a);
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
