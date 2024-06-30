<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Data Diri</template>

    Nama saya
    <a href="" target="_blank" rel="noopener">Azri</a>
    dengan asli orang Pekanbaru yang bertujuan untuk meraih cita-cita yang mulia!. Adapun lengkapnya:
    <ol>
      <li><pre>Nama Lengkap  : M. Rafli Azriansyah</pre></li>
      <li><pre>Panggilan     : Azri, Aji</pre></li>
      <li><pre>TTL           : Pekanbaru, 22 Oktober 2003</pre></li>
      <li><pre>Alamat Rumah  : Jl. H. Imam Munandar Gg. Sawo No. 326</pre></li>
      <li><pre>Jenis Kelamin : Laki-Laki</pre></li>
      <li><pre>Pekerjaan     : Mahasiswa</pre></li>
      <li><pre>Status        : Belum Menikah</pre></li>
    </ol>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan Sekarang</template>

    Saya sekarang sedang berkuliah di
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>. Adapun Program Studi yang saya ambil adalah
    <a href="https://baak.uir.ac.id/" target="_blank" rel="noopener">Teknik Informatika</a> +
    <a href="https://eng.uir.ac.id/" target="_blank" rel="noopener">Fakultas Teknik</a> Dengan NPM adalah 223510644. Bisa dibilang, saya adalah mahasiswa UIR angkatan 2022.
    
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Riwayat Pendidikan</template>

    Adapun Riwayat Pendidikan Lengkap Saya:
    <ul>
      <li><pre>Taman Kanak-kanak         : <a target="_blank" href="https://dapo.kemdikbud.go.id/sekolah/A66E3E908C322C48DFF8">TK Raudhatul Amilin Pekanbaru</a></pre></li>
      <li><pre>Sekolah Dasar             : <a target="_blank" href="https://www.google.com/maps/place/SD+Negeri+83+Pekanbaru/@0.501124,101.464327,724m/data=!3m1!1e3!4m6!3m5!1s0x31d5ae93d9896733:0xf5c9e10e51fdc9!8m2!3d0.5011236!4d101.464327!16s%2Fg%2F11c5r4r2xg?hl=id&entry=ttu">SD Negeri 083 Pekanbaru</a></pre></li>
      <li><pre>Sekolah Menengah Pertama  : <a target="_blank" href="https://www.mtsn1pekanbaru.sch.id/en/blog">MTs Negeri 01 Andalan Pekanbaru</a></pre></li>
      <li><pre>Sekolah Menengah Atas     : <a target="_blank" href="https://www.brosispku.com/pekanbaru-business-directory/merchant/366/ma-hasanah-pekanbaru">MAS Hasanah Pekanbaru</a></pre></li>
      <li><pre>Perguruan Tinggi          : <a href="https://uir.ac.id/" target="_blank">Universitas Islam Riau</a></pre></li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi atau Kesenangan</template>

    Hobi saya? Kalau memang anda kepo masalah hobi atau kesenangan yang sering saya lakukan, berikut adalah daftarnya:
    <ol>
      <li>Bermain Futsal, bisa 2 sampai 3x seminggu. Tapi biasanya 2x Seminggu.</li>
      <li>Menonton Film dan Mendengarkan Musik, itu saya lakukan ketika sedang jenuh atau butuh penyemangat dalam kegiatan saya.</li>
      <li>Menonton Film dan Mendengarkan Musik, itu saya lakukan ketika sedang jenuh atau butuh penyemangat dalam kegiatan saya.</li>
      <li>Belajar Public Speaking, dimulai dengan sering nonton podcast, dan coba berbicara sendiri untuk latihan.</li>
      <li>Senang melakukan Healing atau Travelling.</li>
      <li>Karena saya sudah punya basic Soft Skill walaupun belum tingkat profesional, tetapi saya sering berdiskusi dengan lawan bicara untuk meningkatkan pengetahuan.</li>
      <li>Saya punya senang ketika bermain Bulutangkis, tetapi sudah jarang. Tiap kali dalam sebulan, saya juga senang bermain Voli, walaupun awalnya kesusahan.</li>
    </ol>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Sosial Media</template>

    Untuk menunjukkan Portofolio atau pengalaman dan sharing kegiatan saya, saya mempunyai akun sosmed seperti berikut:
    <ul>
      <li><pre>Instagram : <a href="https://www.instagram.com/mr_azri72/?hl=en" target="_blank" rel="noopener">@mr_azri72</a></pre></li>
      <li><pre>Thread    : <a href="https://www.threads.net/@mr_azri72?xmt=AQGz_h2gaXdLtdpiYTLZ6xrtQzVlOl-i54KbwvdpI0g56Ns" target="_blank" rel="noopener">@mr_azri72</a></pre></li>
      <li><pre>Twitter(X): <a href="https://x.com/AzriRafli03?t=x5W1ZosWu-U1vEfe4yyVCg&s=08" target="_blank" rel="noopener">@AzriRafli03</a></pre></li>
      <li><pre>Telegram  : <a href="http://t.me/RafliAzri" target="_blank" rel="noopener">@RafliAzri</a></pre></li>
      <li><pre>Tiktok    : <a href="https://www.tiktok.com/@srudukdikit?_t=8nd5KI5Maq8&_r=1" target="_blank" rel="noopener">@srudukdikit</a></pre></li>
      <li><pre>Whatsapp  : <a href="" target="_blank" rel="noopener">085271435700</a></pre></li>
    </ul>
  </WelcomeItem>
</template>
