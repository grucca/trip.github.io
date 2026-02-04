<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lazurowe Wybrzeże 2026</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #0066cc; /* Riviera Blue */
            --secondary-color: #f0f7ff;
            --text-dark: #2d3748;
            --text-light: #718096;
            --bg-color: #f8fafc;
        }

        body {
            font-family: 'Poppins', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-dark);
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 500px;
            margin: 0 auto;
            background: #fff;
            border-radius: 24px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.08);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, var(--primary-color), #00c6ff);
            color: white;
            padding: 30px 20px;
            text-align: center;
        }

        .header h1 {
            margin: 0;
            font-size: 26px;
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        .header p {
            margin: 5px 0 0;
            opacity: 0.9;
            font-size: 14px;
        }

        .content {
            padding: 25px;
        }

        /* Sekcja Loty */
        .flights-card {
            background: var(--secondary-color);
            border-radius: 16px;
            padding: 20px;
            margin-bottom: 30px;
            border: 1px solid #dceeff;
        }

        .flights-title {
            font-weight: 600;
            color: var(--primary-color);
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }

        .flights-title::before {
            content: '✈️';
            margin-right: 10px;
        }

        .flight-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 15px;
            font-size: 13px;
        }
        
        .main-flights, .alt-flights {
            padding-bottom: 10px;
        }

        .alt-flights {
            border-top: 1px dashed #cddbea;
            padding-top: 15px;
            color: var(--text-light);
        }

        /* Sekcje Dni - Timeline */
        .day-section {
            margin-bottom: 35px;
        }

        .day-header {
            display: flex;
            align-items: baseline;
            margin-bottom: 20px;
        }

        .day-date {
            font-size: 18px;
            font-weight: 700;
            color: var(--primary-color);
            margin-right: 10px;
        }

        .day-loc {
            font-size: 16px;
            font-weight: 500;
            color: var(--text-dark);
        }

        .timeline {
            position: relative;
            padding-left: 30px;
            border-left: 2px solid #e2e8f0;
        }

        .timeline-item {
            position: relative;
            margin-bottom: 25px;
        }

        .timeline-item:last-child {
            margin-bottom: 0;
        }

        .timeline-dot {
            position: absolute;
            left: -36px;
            top: 5px;
            width: 14px;
            height: 14px;
            border-radius: 50%;
            background: white;
            border: 3px solid var(--primary-color);
        }

        .time-label {
            font-size: 12px;
            font-weight: 600;
            text-transform: uppercase;
            color: var(--text-light);
            margin-bottom: 5px;
            display: block;
        }

        .item-content {
            font-size: 14px;
        }

        .highlight {
            font-weight: 600;
            color: var(--primary-color);
        }

        /* Sekcja Noclegi */
        .nocleg-placeholder {
            text-align: center;
            padding: 20px;
            background: #f8fafc;
            border: 1px solid #e2e8f0;
            border-radius: 16px;
        }

        .nocleg-title {
            font-weight: 600;
            margin-bottom: 15px;
            color: var(--text-dark);
            display: block;
        }

        .hotel-btn {
            display: block;
            background: white;
            color: var(--primary-color);
            text-decoration: none;
            padding: 12px 15px;
            margin-bottom: 10px;
            border-radius: 10px;
            border: 1px solid #dceeff;
            font-size: 13px;
            font-weight: 500;
            transition: all 0.2s ease;
            box-shadow: 0 2px 5px rgba(0,0,0,0.03);
        }

        .hotel-btn:hover {
            background: var(--primary-color);
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 102, 204, 0.2);
        }

        .hotel-btn:last-child {
            margin-bottom: 0;
        }

        .hotel-icon {
            margin-right: 8px;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <h1>Lazurowe Wybrzeże</h1>
        <p>Plan Podróży • Kwiecień 2026</p>
    </div>

    <div class="content">
        <div class="flights-card">
            <div class="flights-title">Loty</div>
            <div class="flight-grid">
                <div class="main-flights">
                    13.04 / <b>Warszawa</b> 7:15 → <b>Nicea</b> 9:50<br>
                    19.04 / <b>Nicea</b> 19:40 → <b>Warszawa</b> 22:00<br>
                    19.04 / <b>Nicea</b> 21:20 → <b>Kraków</b> 23:30
                </div>
                <div class="alt-flights">
                    <i>Alternatywnie:</i><br>
                    18.04 / <b>Nicea</b> 20:20 → <b>Kraków</b> 22:30
                </div>
            </div>
        </div>

        <div class="day-section">
            <div class="day-header">
                <span class="day-date">15 KWI</span>
                <span class="day-loc">Cannes</span>
            </div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Popołudnie / Wieczór</span>
                    <div class="item-content">
                        <span class="highlight">Le Suquet</span> (punkt widokowy), <span class="highlight">Marché Forville</span> (targ), <span class="highlight">Vieux Port</span> (stary port), spacer <span class="highlight">La Croisette</span> i <span class="highlight">Rue d'Antibes</span>.
                    </div>
                </div>
            </div>
        </div>

        <div class="day-section">
            <div class="day-header">
                <span class="day-date">16 KWI</span>
                <span class="day-loc">Monako</span>
            </div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Rano</span>
                    <div class="item-content">
                        <span class="highlight">Monaco-Ville</span> (spacer uliczkami), Katedra św. Mikołaja, <span class="highlight">Pałac Książęcy</span> (zmiana warty 11:55).
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Południe</span>
                    <div class="item-content">
                        Lunch na <span class="highlight">Marché de la Condamine</span> (spróbuj barbagiuan), <span class="highlight">Muzeum Oceanograficzne</span>, Port Hercules i spacer trasą F1.
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Wieczór</span>
                    <div class="item-content">
                        <span class="highlight">Monte Carlo</span>, lobby Grand Casino, Jardin Japonais, Larvotto.
                    </div>
                </div>
            </div>
        </div>

        <div class="day-section">
            <div class="day-header">
                <span class="day-date">17 KWI</span>
                <span class="day-loc">Èze & Villefranche</span>
            </div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Rano</span>
                    <div class="item-content">
                        <span class="highlight">Èze Village</span> (spacer ok. 9:00, Ogród Egzotyczny).
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Południe</span>
                    <div class="item-content">
                        <span class="highlight">Villefranche-sur-Mer</span>, Lunch w porcie, <span class="highlight">Rue Obscure</span>.
                    </div>
                </div>
            </div>
        </div>

        <div class="day-section">
            <div class="day-header">
                <span class="day-date">18 KWI</span>
                <span class="day-loc">Nice I</span>
            </div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Rano</span>
                    <div class="item-content">
                        Targ <span class="highlight">Cours Saleya</span> (socca!), Vieux Nice, lody w <span class="highlight">Fenocchio</span>.
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Południe / Wieczór</span>
                    <div class="item-content">
                        <span class="highlight">Colline du Château</span> (wodospad), Lunch w Port Lympia, Promenada Anglików, Plac Masséna. Kolacja na starym mieście.
                    </div>
                </div>
            </div>
        </div>

        <div class="day-section">
            <div class="day-header">
                <span class="day-date">19 KWI</span>
                <span class="day-loc">Nice II</span>
            </div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <span class="time-label">Rano</span>
                    <div class="item-content">
                        Wzgórze <span class="highlight">Cimiez</span>, Rzymskie Ruiny, Ogrody Klasztorne, <span class="highlight">Muzeum Matisse’a</span>.
                    </div>
                </div>
            </div>
        </div>

        <div class="nocleg-placeholder">
            <span class="nocleg-title">🛏️ Wybrane Noclegi (Booking)</span>
            
            <a href="https://www.booking.com/hotel/fr/big-apartment-t3-neuf-tout-confort-parking-ferme.pl.html?label=gen173nr-10CAEoggI46AdIM1gEaLYBiAEBmAEzuAEXyAEM2AED6AEB-AEBiAIBqAIBuALC2onMBsACAdICJGQ1ZTM4YTFkLWVjN2ItNGI4OC04MjM3LTI5NjNhNjU0MDJiY9gCAeACAQ&aid=304142&ucfs=1&checkin=2026-04-15&checkout=2026-04-19&dest_id=-1454990&dest_type=city&group_adults=3&no_rooms=3&group_children=0&sr_order=price&nflt=review_score%3D80%3Bprice%3DPLN-min-1000-1%3Bprivacy_type%3D3%3Bentire_place_bedroom_count%3D2%3Bnum_beds%3D3&srpvid=e6db06ed3b29f3dc6014697b6eb3966b&srepoch=1770162242&matching_block_id=762867701_333385814_4_0_0_171799&atlas_src=sr_iw_title" class="hotel-btn" target="_blank">
                <span class="hotel-icon">🏨</span> Big Apartment T3 Neuf
            </a>

            <a href="https://www.booking.com/hotel/fr/suite-la-boheme-five-stars-holiday-house.pl.html?label=gen173nr-10CAEoggI46AdIM1gEaLYBiAEBmAEzuAEXyAEM2AED6AEB-AEBiAIBqAIBuALC2onMBsACAdICJGQ1ZTM4YTFkLWVjN2ItNGI4OC04MjM3LTI5NjNhNjU0MDJiY9gCAeACAQ&aid=304142&ucfs=1&checkin=2026-04-15&checkout=2026-04-19&dest_id=-1454990&dest_type=city&group_adults=3&no_rooms=3&group_children=0&sr_order=price&nflt=review_score%3D80%3Bprice%3DPLN-min-1000-1%3Bprivacy_type%3D3%3Bentire_place_bedroom_count%3D2%3Bnum_beds%3D3&srpvid=e6db06ed3b29f3dc6014697b6eb3966b&srepoch=1770162092&matching_block_id=990027603_371686732_4_0_0&atlas_src=sr_iw_title&activeTab=photosGallery" class="hotel-btn" target="_blank">
                <span class="hotel-icon">✨</span> Suite La Boheme
            </a>

            <a href="https://www.booking.com/hotel/fr/share-inn-appartements.pl.html?label=gen173nr-10CAEoggI46AdIM1gEaLYBiAEBmAEzuAEXyAEM2AED6AEB-AEBiAIBqAIBuALC2onMBsACAdICJGQ1ZTM4YTFkLWVjN2ItNGI4OC04MjM3LTI5NjNhNjU0MDJiY9gCAeACAQ&aid=304142&ucfs=1&checkin=2026-04-15&checkout=2026-04-19&dest_id=-1454990&dest_type=city&group_adults=3&no_rooms=3&group_children=0&sr_order=price&nflt=review_score%3D80%3Bprice%3DPLN-min-1000-1%3Bprivacy_type%3D3%3Bentire_place_bedroom_count%3D2%3Bnum_beds%3D3&srpvid=e6db06ed3b29f3dc6014697b6eb3966b&srepoch=1770162092&matching_block_id=750910704_339612263_4_0_0&atlas_src=sr_iw_title&activeTab=photosGallery" class="hotel-btn" target="_blank">
                <span class="hotel-icon">🔑</span> Share Inn Appartements
            </a>

            <a href="https://www.booking.com/hotel/fr/35-suite-carlone-5min-from-the-beach-ac-amp-terrace.pl.html?label=gen173nr-10CAEoggI46AdIM1gEaLYBiAEBmAEzuAEXyAEM2AED6AEB-AEBiAIBqAIBuALC2onMBsACAdICJGQ1ZTM4YTFkLWVjN2ItNGI4OC04MjM3LTI5NjNhNjU0MDJiY9gCAeACAQ&aid=304142&ucfs=1&checkin=2026-04-15&checkout=2026-04-19&dest_id=-1454990&dest_type=city&group_adults=3&no_rooms=3&group_children=0&sr_order=price&nflt=review_score%3D80%3Bprice%3DPLN-min-1000-1%3Bprivacy_type%3D3%3Bentire_place_bedroom_count%3D3%3Bnum_beds%3D3&srpvid=e6db06ed3b29f3dc6014697b6eb3966b&srepoch=1770162599&matching_block_id=1392059901_411170460_4_0_0&atlas_src=sr_iw_title&activeTab=photosGallery" class="hotel-btn" target="_blank">
                <span class="hotel-icon">🌴</span> 35 Suite Carlone
            </a>
        </div>

    </div>
</div>

</body>
</html>
