# Student Portfolio

My portfolio for Assignment 4. Create `prf-network` first, then run:

```bash
docker build -t studentportfolio .
docker run -d --name studentportfolio --network prf-network -p 3000:80 studentportfolio
```

Open: http://192.168.56.53:3000

Based on the [course template](https://github.com/Feranmi-A/Studentportfoliotemplate).
