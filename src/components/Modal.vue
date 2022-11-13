<template>
    <div class="portfolio-modal modal fade" id="{{name}}" tabindex="-1" aria-labelledby="{{name}}" aria-hidden="true">
        <div class="modal-dialog modal-xl">
            <div class="modal-content">
                <div class="modal-header border-0"><button class="btn-close" type="button" data-bs-dismiss="modal" aria-label="Close"></button></div>
                <div class="modal-body text-center pb-5">
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <!-- Portfolio Modal - Title-->
                                <h2 class="portfolio-modal-title text-secondary text-uppercase mb-0">AMED STAT</h2>
                                <!-- Portfolio Modal - Text-->
                                <p class="mb-4">ระบบสถิติข้อมูลการให้บริการของหน่วยสายแพทย์</p>
                                <!-- Icon Divider-->
                                <div class="divider-custom">
                                    <div class="divider-custom-line"></div>
                                    <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
                                    <div class="divider-custom-line"></div>
                                </div>
                                <!-- Portfolio Modal - Image-->
                                <img class="img-fluid rounded mb-3" src="@/assets/images/portfolio/amedstat/login.png" alt="..." />
                                <img class="img-fluid rounded mb-3" src="@/assets/images/portfolio/amedstat/dashboard.png" alt="..." />
                                <img class="img-fluid rounded mb-3" src="@/assets/images/portfolio/amedstat/inform.png" alt="..." />
                                <img class="img-fluid rounded mb-3" src="@/assets/images/portfolio/amedstat/report.png" alt="..." />
                                <button class="btn btn-primary" data-bs-dismiss="modal">
                                    <i class="fas fa-xmark fa-fw"></i>
                                    Close Window
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: ['name'],
    mounted() {
        console.log(this.name)
    }
}
</script>

<style>

</style>