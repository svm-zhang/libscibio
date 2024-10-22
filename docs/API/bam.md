# Module dealing with anything related to BAM file

::: libscibio.bam
    options:
        filters:
            - "!^_"
            - "!^__"
        member:
            - BAMetadata
            - parse_cigar
            - parse_md
            - count_soft_clip_bases
            - count_unaligned_events
            - count_indel_events
            - count_indel_bases
            - count_mismatch_events