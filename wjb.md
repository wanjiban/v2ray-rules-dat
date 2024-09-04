      - name: Get geoip.dat relative files
        run: |
          wget https://github.com/wanjiban/geoip/raw/release/geoip.dat
          wget https://github.com/wanjiban/geoip/raw/release/geoip.dat.sha256sum
      - name: Generate GFWList domains
        run: |
