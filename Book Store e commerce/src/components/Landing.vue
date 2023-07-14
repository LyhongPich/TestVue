<script>
    import Logo from './Logo.vue'
    import Book from './Book.vue'
    export default {
        components: {
            Logo,
            Book,
        }
    }
</script>

<template>
    <div class="w-full h-[779px] flex justify-center items-center">
        <div class="w-[90%] h-auto flex flex-col justify-center">
            <div class="w-full flex items-center h-[224px]">
                <span class="w-[45%] text-8xl font-bold text-center">About Books</span>
                <div class="w-full flex items-center justify-center">
                    <Logo class="w-[11%] h-[192px]" url="https://m.media-amazon.com/images/I/51wwAE5J6EL._AC_UF1000,1000_QL80_.jpg"></Logo>
                    <Logo class="w-[11%] h-[192px] mx-[2%]" url="https://goodbookscents.files.wordpress.com/2013/04/the-book-thief.jpg?w=291&h=449"></Logo>
                    <Logo class="w-[11%] h-[192px]" url="https://i0.wp.com/www.thebooksmugglers.com/wp-content/uploads/2012/02/The-Guernsey-Literary-and-Potato-Peel-Pie-Society.jpg"></Logo>
                    <Logo class="w-[11%] h-[192px] mx-[2%]" url="https://www.nationalbook.org/awards2021/covers/fic-Hell%20of%20a%20Book%20by%20Jason%20Mott.jpg"></Logo>
                    <Logo class="w-[11%] h-[192px]" url="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1573289838l/51932121.jpg"></Logo>
                </div>
            </div>
            <span class="w-full text-[2.5em] font-bold h-[48px] text-center mb-[30px]">Best Sell</span>
            <div class="w-full flex justify-between items-center h-[286px]">
                <Book class="w-[17%] h-full" 
                    url="https://static.wixstatic.com/media/ea71bb_17c5485b41484f82b42aaa8a17474342~mv2_d_2479_2483_s_4_2.jpg/v1/fill/w_279,h_279,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/ea71bb_17c5485b41484f82b42aaa8a17474342~mv2_d_2479_2483_s_4_2.jpg"
                    title="Book 1"
                    price="$20.00">
                </Book>
                <Book class="w-[17%] h-full" 
                    url="https://static.wixstatic.com/media/ea71bb_30bb0bbedfa6425380becfdccd67d02b~mv2_d_2479_2483_s_4_2.jpg/v1/fill/w_224,h_224,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/ea71bb_30bb0bbedfa6425380becfdccd67d02b~mv2_d_2479_2483_s_4_2.jpg"
                    title="Book 2"
                    price="$18.50">
                </Book>
                <Book class="w-[17%] h-full" 
                    url="https://static.wixstatic.com/media/ea71bb_0f554db9ccd946dfb1f67dad05d6a2ba~mv2_d_2479_2483_s_4_2.jpg/v1/fill/w_224,h_224,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/ea71bb_0f554db9ccd946dfb1f67dad05d6a2ba~mv2_d_2479_2483_s_4_2.jpg"
                    title="Book 3"
                    price="$25.75">
                </Book>
                <Book class="w-[17%] h-full" 
                    url="https://static.wixstatic.com/media/ea71bb_88f750dd06704bee9c4bed3acebaec54~mv2_d_2479_2483_s_4_2.jpg/v1/fill/w_224,h_224,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/ea71bb_88f750dd06704bee9c4bed3acebaec54~mv2_d_2479_2483_s_4_2.jpg"
                    title="Book 4"
                    price="$27.00">
                </Book>
            </div>
            <div class="w-full flex items-center justify-between opacity-50">
                <Logo class="w-[22%] h-[96px]" url="https://booklistqueen.com/wp-content/uploads/booklist-queen-logo-2.png"></Logo>
                <Logo class="w-[22%] h-[96px]" url="https://logos-world.net/wp-content/uploads/2020/10/Wix-Logo-2012-2013.png"></Logo>
                <Logo class="w-[22%] h-[96px]" url="https://m.media-amazon.com/images/G/01/gc/designs/livepreview/a_generic_white_10_us_noto_email_v2016_us-main._CB627448186_.png"></Logo>
            </div>
        </div>
    </div>
</template>